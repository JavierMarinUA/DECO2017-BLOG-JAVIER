---
title: A3 Reflection
date: 2026-05-16
author: Javier Marin Ferrandiz
summary: We refined PopKorner by adding motivational API content, custom task creation and early user testing through a think-aloud activity.
tags:
  - Prototyping
  - User Testing
  - API
  - Functional Requirements
  - Evaluation
---


For this reflection blog we will talk about how all turned out and what are the results from our work. I will show details and explications about different sections of the aplication web and make a refection about those to see how it turned at the end of the developemet.

We will separate the explications in four different sections. Performance and technical behaviour, User Experience and accessibility, Critical Reflection and Improvement Planning and lastly Retrospective Assessment of Functional Requirements.

1. Performance

- The times for charging are fast and they don't have any delay. We have tested the aplication web in diferent browsers as seen in the screenshots of Google and Microsoft Edge and both work on a efective and eficient way without long charge screens or DB delays. Even when the user compleets a task the charging time for the stats to update is instant and the user can see the progress instantly.
(image) - browser1
(image) - browser2

- About the responsiveness we have an aplicantion web absolutely responssive, ready to use either in computer, tablet or phone. We have 3 different levels of resposive dispositions of the web as shown in the following imgaes. This helps the user to have a clear vision of the aplication web in any platform or device. Thanks to this our users would be able to use the same account in diferent devices with any plroblem.
(image) -responsive1
(image) -responsive2
(image) -responsive3

- We have used multiple tools to check if the efficiency of our web aplication had a professional standard. We have runed the test tools we had in the template as well as our tests. 

npm run build:test (on code format)

(image) build:test

Here we see in the image how we have a PASS on all the tests.

npm run lint (on code format)

(image) lint test

Here we have another good feedback from the lint test. This test performs static code analysis to detect syntax errors, code quality issues, and style violations before deployment.

We have also used the Lighthouse tool from google's browser that gives us feedback about various aspects of the website. 

(image) -The 4 circles of performance in lighthouse

We can see how this tool shows that we have an overall strong performance. Beeing the Accessibility and the Best Practices the two beter valuated aspects. Then we have a good SEO and Performance with some recomendations for inprovement as using efficient cache lifetimes or improving the image delivery. We already used this tool to change slightly some parts of the project in the visual part. It is a very strong tool that we colud use to improve our web aplication in the future if we had more time to work on it focusing on the SEO and Performance recomendations.



2. Evaluation of User Experience and Accessibility


- As we can see in the final design of our feed we had used a soft and undertandable color palette using white and orange tones. In this way, we developed a user-friendly interface that makes the website clear and intuitive to navigate. Key actions, such as the Publish button, are given greater visibility to encourage user interaction and engagement.

(image) - Final feed web

- We can also se the this pattern in the Avatar window with CREATE TASK button or the COMPLETE button, encouraging the user interaction again. This makes a strong clarity for the interactions from the users to the website.

- If we look at the first blog posts, we can see that we created a mockup of the website's design, aiming to follow a soft color aesthetic. So we are very happy with the result of what we have reached on the last version of the web aplication.

(image) - Initial mockups in planning

- We have also did user testing during one of the tutorials. We made three think aloud tests. This was very helpful as we got good feedback to change some aspects of the website, like the selection of differents avatars, to customize the experience of the user. We had this idea on the wirefriming developement but we removed it, then thanks to the user testing we added it. Thanks to one of the user testing we came up with the idea of making a visual timer that showed in real time the time left for the day to restart and refresh with new tasks. Testers really liked the interface and the appareance of the website and said that all the options were clear and easy to find and understand.

(image) - avatar section
(image) - timer countdown


3. Critical Reflection and Improvement Planning

- We think we did a good job overall but we could have made more features that would have caused in a more completed aplication web.

- One of the improvements that could be implemented in the future is the introduction of different profile types tailored to the specific areas users wish to develop. For example, profiles could be designed to support study productivity, healthy eating habits, or other personal goals, instead of focusing exclusively on sports and fitness. This would result in a more personalized user experience.

- If we would continue the developement we could also add a detailed section for food management. To give the user the option to track their food habits and to show if they are following a good or a poor diet. This would be added as a part of the sportive/healty avatar. This could make the user more interested in following better food habits and interact more constantly with the app, resulting in better user retention.

- We succeded but because we focused on refining our main functional requirements as detailed as possible. Nevertherless, we could have added more fuatures that could have resulted on a more completed product.  


4. Retrospective Assessment of Functional Requirements

Consider what you learned through the development process. This could relate to technical skills, project scoping, design decisions, or anything else that shaped your understanding of web development.

- If we see the firsts blogs we will se how we made a mockup with the possibe interaction of the user compleeting the tasks. We have reached exactly the goals we had in the planning phase, making the avatar stats, levels, tasks and creation of original tasks. We have even added the clock feature, that shows the time remaining of the daily tasks and when are they going to be reseted with new tasks. Nevertheless we have done some changes on the aproach of the pages distribution.

- We changed the way that the website looks and the navigation to just two pages to make it clearer. We came up with the conclussion that more pages just made the user experience worse. The functional requirement of creating a task was added in the avatar page as well as the avatar selection.

- Thanks to one of the tutorials we added an API that shows different motivational sentences each time you refresh the website or you click the referesh button. This feature is called daily sparks, adding another functional requirement to the aplication web.

- I think we did a very good job overall. We had made some changes from the very first model of the website, keeping the functional requirements and adding some, but I think that those changes were made for good and result in a cleaner and clearer website for the user.