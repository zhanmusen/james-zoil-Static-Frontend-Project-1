# Manual Testing for Midnight Echo Website

This document records the full manual testing process for the Midnight Echo static front end website.  
It covers functionality, usability, responsiveness, accessibility, and alignment with user stories.  
All tests were carried out on both the development version and the deployed version to confirm that they match.

---

## Test environment

Browsers used  
1. Google Chrome on desktop  
2. Mozilla Firefox on desktop  
3. Safari on iPhone  
4. Chrome on Android  

Screen sizes tested  
1. Large desktop  
2. Laptop  
3. Tablet  
4. Mobile portrait  
5. Mobile landscape  

Assistive checks  
1. Screen reader navigation  
2. Keyboard only navigation  
3. Colour contrast inspection  

---

## Test cases

Each test case includes the feature, scenario, steps, expected result, actual result, and outcome.

---

## Navigation tests

**TC 1**  
Feature: Main navigation  
Scenario: User clicks each menu item  
Steps  
1. Open the site  
2. Click Home  
3. Click About  
4. Click Shows and Booking  
Expected result: Each link loads the correct page  
Actual result: All links load correctly  
Outcome: Pass  

**TC 2**  
Feature: Active page indicator  
Scenario: User views any page  
Steps  
1. Open each page  
Expected result: The current page link is clearly highlighted  
Actual result: Highlight appears correctly  
Outcome: Pass  

---

## Content and media tests

**TC 3**  
Feature: Audio players  
Scenario: User plays audio samples  
Steps  
1. Open the Home page  
2. Press play on each audio track  
Expected result: Audio plays only when the user presses play  
Actual result: Audio behaves correctly  
Outcome: Pass  

**TC 4**  
Feature: Embedded video  
Scenario: User views the live performance video  
Steps  
1. Scroll to the video section  
Expected result: Video loads and remains paused until the user presses play  
Actual result: Video behaves correctly  
Outcome: Pass  

**TC 5**  
Feature: Images  
Scenario: User views all images  
Steps  
1. Open all pages  
2. Inspect each image  
Expected result: Images load clearly with no pixelation or stretching  
Actual result: All images display correctly  
Outcome: Pass  

---

## Shows and booking page tests

**TC 6**  
Feature: Shows table  
Scenario: User reads upcoming dates  
Steps  
1. Open the Shows page  
Expected result: Table displays correctly with readable text  
Actual result: Table displays correctly  
Outcome: Pass  

**TC 7**  
Feature: Ticket links  
Scenario: User clicks ticket links  
Steps  
1. Click each ticket link  
Expected result: Links open in a new tab  
Actual result: All links open in a new tab  
Outcome: Pass  

**TC 8**  
Feature: Booking information  
Scenario: User reads booking details  
Steps  
1. Scroll to the booking section  
Expected result: All information is clear and easy to understand  
Actual result: Content is clear  
Outcome: Pass  

---

## Responsiveness tests

**TC 9**  
Feature: Layout on mobile  
Scenario: User views the site on a mobile device  
Steps  
1. Open the site on a phone  
Expected result: Layout adjusts correctly with readable text and no overflow  
Actual result: Layout behaves correctly  
Outcome: Pass  

**TC 10**  
Feature: Layout on tablet  
Scenario: User views the site on a tablet  
Steps  
1. Open the site on a tablet  
Expected result: Grid sections adjust smoothly  
Actual result: Layout behaves correctly  
Outcome: Pass  

**TC 11**  
Feature: Navigation on small screens  
Scenario: User interacts with the menu on mobile  
Steps  
1. Open the site on a phone  
Expected result: Navigation remains clear and easy to use  
Actual result: Navigation behaves correctly  
Outcome: Pass  

---

## Accessibility tests

**TC 12**  
Feature: Colour contrast  
Scenario: User checks contrast  
Steps  
1. Inspect text and background colours  
Expected result: All text meets accessibility contrast guidelines  
Actual result: Contrast is acceptable  
Outcome: Pass  

**TC 13**  
Feature: Alternative text  
Scenario: User checks image descriptions  
Steps  
1. Inspect all images  
Expected result: All images contain descriptive alternative text  
Actual result: All images include correct alternative text  
Outcome: Pass  

**TC 14**  
Feature: Keyboard navigation  
Scenario: User navigates without a mouse  
Steps  
1. Use the Tab key to move through the site  
Expected result: All interactive elements are reachable in a logical order  
Actual result: Keyboard navigation works correctly  
Outcome: Pass  

---

## Bugs found and fixes applied

**Bug 1**  
Issue: Shows table overflowed slightly on very small screens  
Fix: Added responsive table styling and allowed horizontal scroll  
Status: Fixed  

**Bug 2**  
Issue: One image lacked alternative text  
Fix: Added descriptive alternative text  
Status: Fixed  

---

## Remaining known issues

**Issue 1**  
The shows table requires horizontal scrolling on very narrow screens.  
This is acceptable for the current scope and does not affect usability.

---

## Alignment with user stories

1. New visitors can understand the band and their style from the Home page content  
2. Fans can listen to audio samples and watch a video  
3. Event organisers can view pricing guidance and booking details  
4. Social media links are available in the footer on every page  

All user stories are fully satisfied.

---

## Conclusion

All essential features work correctly.  
The site is responsive, accessible, and aligned with the project purpose.  
The deployed version matches the development version with no broken links or missing content.
