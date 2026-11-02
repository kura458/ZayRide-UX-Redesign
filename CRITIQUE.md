\# ZayRide Passenger App — UI/UX Critique



\## 1. Introduction



This document evaluates the user interface (UI) and user experience (UX) of ZayRide Passenger, an Ethiopian ride-booking application. The purpose is to identify usability strengths, possible weaknesses, and opportunities for improvement before developing an Android XML redesign.



The evaluation uses publicly available information, archived screenshots of the Passenger application, and information published on the official ZayRide website.



\*\*Evaluation limitation:\*\* I do not have access to a physical smartphone or a working installation of ZayRide Passenger. Therefore, I could not personally test the live application, create a real booking, or verify its current performance. This critique is based on archived visual references and public information, not hands-on testing.



\## 2. Application Overview



ZayRide is an Ethiopian transportation service. Its official website describes a process in which a passenger requests a trip, gets matched with a driver, takes the trip, and pays and rates the service.



The website also describes services in Ethiopian cities and mentions delivery services.



The Passenger application was previously distributed through Google Play under the package name `com.zayride.passenger`. Public app-listing archives report that it was removed from Google Play in May 2025. The exact removal date differs between archive sources.



\*\*Sources:\*\*

\- Official website: https://www.zayride.com/

\- Chrome-Stats archived listing: https://chrome-stats.com/d/com.zayride.passenger

\- AppBrain archived listing: https://www.appbrain.com/app/zayride-passenger/com.zayride.passenger



\## 3. UI Evaluation



The following areas should be examined against the archived screenshots saved in the `ScreenShuts` folder.



\### 3.1 Layout and organization



The main home and booking screens are important because they support the passenger's main task: requesting transportation.



During the redesign, the home screen will prioritize the destination and pickup information. The booking screen will organize available ride choices and estimated fares so that users can understand their options before confirming.



\*\*Visual evidence to add:\*\* Insert observations from `02-home.png` and `03-booking.png` after checking the actual images.



\### 3.2 Visual hierarchy



A ride-booking interface should make the most important actions easy to recognize. Pickup location, destination, ride selection, fare information, and confirmation should have clear visual priority.



The redesign will use a prominent primary action for finding or confirming a ride, while supporting information will use smaller and less visually dominant text.



\### 3.3 Typography and readability



Text should be readable at common Android screen sizes. Important labels should be easy to distinguish from supporting descriptions.



The redesign will use consistent text sizes, clear labels, and sufficient contrast between text and backgrounds.



\### 3.4 Color and consistency



The redesign will use a consistent blue primary color, neutral backgrounds, and reusable button and card styles. Repeated components should have consistent corner radii, spacing, and typography.



The exact colors and typography of the original app should be recorded only after examining the archived screenshots.



\## 4. UX Evaluation



\### 4.1 Main user task



The central passenger task is to request a ride. A clear interface should guide users through:



1\. Entering or selecting a pickup location.

2\. Entering a destination.

3\. Reviewing available ride options and estimated fares.

4\. Confirming the ride.

5\. Following the trip and reviewing its completion.



The redesign will organize its screens around this sequence.



\### 4.2 Navigation



The home screen should provide a clear starting point for booking. Supporting areas such as trips and profile information should not distract users from the primary ride-booking task.



The redesign will use simple navigation labels and a consistent screen structure.



\### 4.3 Accessibility



The redesign will consider the following accessibility principles:



\- Use readable text and sufficient color contrast.

\- Use clear labels rather than relying only on icons.

\- Provide adequately sized touch targets, aiming for approximately 48dp where practical.

\- Avoid overcrowding the screen.

\- Keep important actions visually distinct.



\### 4.4 Low-end devices and connectivity



Users may have different Android devices, screen sizes, and network conditions. A useful redesign should avoid unnecessary visual complexity and keep the main booking information clear.



A production-ready application should also communicate loading, network failure, empty results, and booking errors clearly. These behaviors are design recommendations; they have not been verified in the archived application.



\### 4.5 Feedback and error handling



The redesign should provide clear feedback after important actions. For example, users should receive confirmation when a ride request is submitted and understandable messages when required information is missing or a request fails.



These are proposed improvements, not claims about the original app's current behavior.



\## 5. Comparison with the Previous Student's Design



This section must be completed after identifying and inspecting the previous student's actual wireframe or redesign.



The comparison should cover:



\- Screen layout and organization.

\- Visual hierarchy and readability.

\- Navigation and number of steps for the main task.

\- Consistency of buttons, icons, and typography.

\- Accessibility and touch-target sizes.

\- Improvements introduced in this redesign.



\*\*Evidence required:\*\* Add the previous student's repository link, identify the exact design/screens inspected, and include screenshots where permitted. Do not claim that a previous student's design was inspected until this has been done.



\## 6. Proposed Improvements



This redesign focuses on three core screens:



\### Screen 1: Welcome



\- Introduce the ZayRide redesign clearly.

\- Use a prominent starting action.

\- Keep the screen visually simple.



\### Screen 2: Home / Find a Ride



\- Make pickup and destination information easy to locate.

\- Give the main ride-search action strong visual priority.

\- Keep supporting navigation simple.



\### Screen 3: Choose Your Ride



\- Present ride categories and estimated fares clearly.

\- Make the selected ride easy to identify.

\- Show the estimated fare before confirmation.

\- Provide a clear confirmation action.



The redesigned screens are static UI prototypes. They do not connect to ZayRide's live booking, driver tracking, payment, or location services.



\## 7. Limitations



\- The Passenger app is no longer listed on Google Play according to public app archives.

\- The original app could not be installed and tested on a physical smartphone.

\- The evaluation relies on archived screenshots and public information.

\- Current availability and operation of the passenger service could not be independently verified.

\- The Android XML prototype demonstrates interface design, not a working ride-booking service.



\## 8. Conclusion



ZayRide provides a useful case study for redesigning an Ethiopian ride-booking interface. This project focuses on making the passenger journey easier to understand through a clear welcome screen, an organized ride-search screen, and a readable ride-selection screen.



The redesign applies UI/UX principles such as visual hierarchy, consistency, readability, accessibility, and clear feedback. Further evaluation would require testing with users and access to a working version of the original application.



\## 9. References and AI Assistance



1\. ZayRide official website: https://www.zayride.com/

2\. Chrome-Stats, ZayRide Passenger archived listing: https://chrome-stats.com/d/com.zayride.passenger

3\. AppBrain, ZayRide Passenger archived listing: https://www.appbrain.com/app/zayride-passenger/com.zayride.passenger

4\. Google Play Help, app availability: https://support.google.com/googleplay/answer/12246761





