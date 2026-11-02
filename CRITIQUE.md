# ZayRide UI/UX Critique

## 1. Introduction

ZayRide is an Ethiopian ride-hailing service that connects passengers with taxi drivers. Its purpose is to make transportation easier by allowing passengers to request rides through a mobile application.

This critique examines the available public information about ZayRide and evaluates the proposed redesign of its passenger booking experience.

**Evaluation note:** Public descriptions were used for this initial review. The actual passenger application and previous student's redesign must also be inspected before this critique is submitted as a final evaluation.

## 2. Existing Application Overview

According to ZayRide's official website, its general booking process includes:

1. The passenger requests a trip and sets a destination.
2. The system matches the passenger with a nearby available driver.
3. The passenger completes the trip.
4. The passenger pays and rates the driver.

The official website also mentions cash and digital payment options.

The public Google Play listing describes features such as:
- Map-based booking and location detection.
- Multiple vehicle categories.
- Fare estimates before booking.
- Promo codes.
- Driver and passenger ratings.

**Source limitation:** The Google Play listing reviewed for this section is titled *ZayRide Driver*. Its features should not automatically be treated as direct observations of the passenger app.

## 3. UI Evaluation

### 3.1 Layout and Visual Hierarchy

The proposed redesign uses three main screens:

- Welcome Screen: introduces the service and provides a starting action.
- Home Screen: presents pickup and destination fields.
- Ride Selection Screen: displays ride choices and an estimated fare.

The design uses a consistent blue-and-white color scheme. Blue highlights important actions, while dark text and lighter secondary text establish visual hierarchy.

**What works well in the proposed design:**
- Clear screen titles.
- Consistent colors.
- Familiar ride-booking interface elements.
- Visible primary buttons.

**What needs improvement:**
- The map is currently a static placeholder.
- Vehicle selection needs a clear selected state.
- The destination and pickup fields should have stronger visual distinction.
- Actual app screenshots must be inspected to make a fair comparison.

### 3.2 Typography and Readability

The redesign uses larger text for headings and smaller text for descriptions and supporting information.

This helps users identify important information quickly.

Further improvements should include:
- Maintaining readable text sizes.
- Using sufficient contrast.
- Avoiding unnecessary decorative fonts.
- Supporting users who view the screen outdoors.

### 3.3 Spacing and Consistency

The redesign uses consistent margins, padding, and spacing between interface elements.

Consistent spacing helps users understand which elements belong together and reduces visual clutter.

## 4. UX Evaluation

### 4.1 Main User Task

The main task is to request a ride.

The proposed interface organizes the process into three understandable stages:

1. Welcome to the service.
2. Enter pickup and destination locations.
3. Select a ride and review its estimated fare.

This structure is intended to make the booking process easier to understand.

### 4.2 Navigation

The Home Screen includes a simple bottom navigation concept with Home, Trips, and Profile.

This gives users recognizable destinations within the application.

The current design is a static prototype. Navigation behavior has not yet been implemented.

### 4.3 Accessibility

The redesign should consider:
- Readable text and sufficient color contrast.
- Touch targets around 48dp or larger.
- Clear labels for buttons and location fields.
- Meaningful icons supported by text.
- Simple layouts that are easy to understand.

### 4.4 Performance and Connectivity

Users may have different Android devices and network conditions.

The application should consider:
- Lightweight screens.
- Avoiding unnecessarily large images.
- Loading indicators while maps or ride information load.
- Clear error messages when internet connectivity is unavailable.
- Useful feedback when no drivers are available.

These are recommendations for the redesign, not verified observations about the current ZayRide application.

## 5. Comparison with the Previous Student's Design

**Complete this section after inspecting the previous student's repository and design.**

Previous student's repository: [Insert repository link]

| Evaluation area | Previous design | My redesign |
|---|---|---|
| Layout | To be inspected | Three-screen booking flow |
| Color | To be inspected | Blue and white |
| Typography | To be inspected | Clear heading hierarchy |
| Navigation | To be inspected | Home, Trips, Profile concept |
| Accessibility | To be inspected | Larger touch areas and readable text |
| Booking flow | To be inspected | Welcome, location entry, ride selection |

I will use actual screenshots and specific examples from the previous design to complete this comparison.

## 6. Proposed Improvements

The redesign focuses on the following improvements:

1. Make the welcome screen clear and welcoming.
2. Place pickup and destination fields prominently.
3. Present vehicle choices in separate, readable cards.
4. Show estimated fare information clearly.
5. Use consistent spacing, colors, and typography.
6. Consider accessibility and low-connectivity situations.

## 7. Limitations

This initial critique is based partly on publicly available descriptions of ZayRide and the proposed XML prototype.

The following work is still required:

- Inspect the actual passenger app.
- Capture screenshots of the real app.
- Inspect a previous student's fork and redesign.
- Replace assumptions with direct observations.
- Test the prototype at two screen sizes.

The XML prototype is static and does not implement real ride booking, GPS, payment, or driver tracking.

## 8. Conclusion

The proposed redesign aims to make the ride-booking experience easier to understand through a clear visual hierarchy, consistent styling, and a simple three-screen flow.

The final design will be refined after comparing it with the actual ZayRide passenger application and a previous student's work.

## 9. References

1. ZayRide Official Website: https://www.zayride.com/
2. ZayRide Driver on Google Play: https://play.google.com/store/apps/details?id=com.zayride.driver
3. ZayRide Ethiopia Telegram channel: https://t.me/zayride

**AI assistance disclosure:** ChatGPT was used to help organize the critique, suggest evaluation criteria, and draft parts of the documentation. The student must personally inspect the application, verify observations, capture screenshots, and revise the analysis before submission.
