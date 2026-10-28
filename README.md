# DemoBlaze E-commerce — Manual QA Testing

## Project overview
A portfolio project demonstrating hands-on manual testing of the DemoBlaze demo e-commerce website.

**Application under test:** https://www.demoblaze.com/

## Objectives
- Practice functional and negative testing of common e-commerce flows.
- Write structured test cases with preconditions, steps, expected results, and actual results.
- Record observed behavior and potential validation gaps without overstating findings.
- Capture screenshots as test evidence.

## Scope covered
- Product details and category filtering
- Cart additions, duplicate entries, deletion, and subtotal calculation
- Checkout form behavior and input-validation observations
- Sign-up, login, logout, and invalid login scenarios
- Closing Login, Sign up, Contact, and About Us modals
- Homepage carousel
- Home navigation and browser Back/Forward
- Product listing pagination

## Project files
- `Test-Cases.xlsx` — executed test cases and recorded results.
- `Bug-Reports.xlsx` — potential defects/validation observations requiring triage.
- `Evidence/` — selected screenshots from login validation tests.

## Test approach
Manual testing was performed in a web browser. Test cases include positive, negative, boundary/input-validation, navigation, and functional checks. Actual results are based on observations reported during execution.

## Results and interpretation
The workbook contains 43 test cases. Review the workbook before publishing or quoting final execution statistics.

Some checkout findings are classified as **potential defects** or **potential validation gaps**, not confirmed defects. The site is a demo application and formal requirements were not provided. In particular:
- Completing a purchase with an empty cart appears inconsistent with typical e-commerce behavior, but the expected rule should be confirmed.
- Acceptance of malformed card/expiry inputs is an observed validation weakness; exact requirements are unavailable.
- Country, City, Month, and Year were observed to be non-mandatory in some tests. They are not reported as defects merely for being blank.

## Environment
Browser and operating-system versions were not recorded during test execution. Add them if known before final publication.

## Limitations
- This is a practice project against a public demo application, not a production system.
- No real payment details were used; continue to use dummy data only.
- Some expected results are based on common e-commerce expectations rather than a formal specification.
- The screenshots included here cover selected login validation tests only. Capture and add evidence for checkout findings before presenting them as finalized defect reports.

## Suggested next improvements
1. Review all test cases for accuracy and fill in any missing execution details.
2. Capture evidence for each reproducible potential defect.
3. Reclassify findings after checking expected behavior and severity/priority.
4. Update this README with actual test execution counts after final review.
