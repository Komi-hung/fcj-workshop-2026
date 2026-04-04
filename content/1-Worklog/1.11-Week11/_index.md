---
title: "Week 11 Worklog"
date: 2024-01-01
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---


### Week 11 Objectives:

* Integrate the Skin AI Analytic model to run directly on the web platform (Client-side), without using APIs.
* Deploy the website to AWS Amplify, optimize performance, and test all functionalities.

### Tasks Performed:

| Day | Task                                                                                                                                            | Start Date | Completion Date | Reference Material |
| --- | ----------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | --------------- | ------------------ |
| 2   | - Review the system architecture, transition the AI processing flow to the Frontend. <br> - Initialize the project and configure the AWS Amplify environment. | 03/16/2026 | 03/16/2026      |                    |
| 3   | - Configure and load the `.tflite` model file directly into the web browser.                                                                    | 03/17/2026 | 03/17/2026      |                    |
| 4   | - Write image preprocessing scripts and feed them into the scoring model directly on the browser without calling a backend API.                 | 03/18/2026 | 03/18/2026      |                    |
| 5   | - Test the local direct analysis functionality, ensuring absolutely no image data is pushed externally or stored.                               | 03/19/2026 | 03/19/2026      |                    |
| 6   | - Deploy the web application to AWS Amplify. <br> - Test on the Amplify environment, fix bugs, and handle edge cases.                           | 03/20/2026 | 03/20/2026      |                    |
| 7   | - Test the processing performance of the web app on Amplify from various devices (PC, Mobile). <br> - Check the automated CI/CD flow and prepare the demo version. | 03/21/2026 | 03/21/2026      |                    |

### Achieved Results:

* Successfully integrated AI running directly on the browser, ensuring absolute data privacy (no images saved).
* Successfully deployed the website, operating smoothly and securely on the AWS Amplify platform.
* Completely offloaded the backend server, fully utilizing Amplify's automated deployment (CI/CD) capabilities.
* Finalized the ultimate web app version in preparation for the demo.