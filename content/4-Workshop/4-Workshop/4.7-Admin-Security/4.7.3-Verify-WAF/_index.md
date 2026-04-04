---
title : "Verify WAF"
date : 2026-04-03
weight : 3
chapter : false
pre : " <b> 4.7.3. </b> "
---

#### Monitor and Verify the Defense System

Your firewall has been successfully set up. The final step in the security section is to verify whether the Rules are actively working and blocking malicious requests.

---

#### Step 1: Monitor the Dashboard

1. From the successful Web ACL creation interface in the previous step, click on the name of your Web ACL (`ecommerce-waf-acl`).
2. Switch to the **Traffic overview** or **Bot control** tab (if available).
3. Here, AWS WAF provides a real-time chart displaying the total number of allowed requests and the number of blocked requests.
4. If the system is newly created, this chart might be empty. Wait a few minutes or proceed to the next step to generate simulation data.


#### Step 2: Test the Rate-limit Rule

To test whether the anti-AI spam rule (`Block-AI-Spam`) is working, we will simulate the behavior of a spam bot.

1. Open your E-commerce website in a browser.
2. Navigate to the AI Chatbot product consultation feature.
3. Start continuously sending short messages or press F5 (reloading the API call continuously) very quickly. The goal is to exceed 100 requests in a very short time (as you configured).
4. If the rule works correctly, after a certain number of requests, your website will start returning errors (usually a 403 Forbidden error). At this point, your IP has been temporarily blocked by the firewall.


#### Step 3: Analyze Blocked Request Logs

1. Return to the **Traffic overview** tab on the AWS WAF console.
2. The chart will now show red columns (or Blocked status) corresponding to your spamming action.
3. Scroll down to the **Sampled requests** section. Here, you will see a detailed list of blocked requests, including the source IP address, country, time, and most importantly, the **Rule name** that executed the block (In this case, it should display `Block-AI-Spam`).
4. The firewall correctly identifying and blocking based on the specific rule proves that your defense system is working perfectly.
