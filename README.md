# Lab 7

## Check Your Understanding

1) I would choose **Option 1: Within a GitHub Action that runs whenever code is pushed**.

I think this is the best option because it makes testing part of the normal development pipeline instead of something I have to remember to do manually. If a new change breaks the Recipe project, the tests can catch the problem right away before the broken code gets merged or deployed. Manually running tests locally is still helpful, but it is easier to forget. Waiting until all development is completed is also too late because bugs would be harder to find and fix.

2) No, I would not use an end-to-end test just to check if a function is returning the correct output. That is better suited for a unit test because it focuses on one small function directly. End-to-end tests are better for testing a full user flow, like loading the page, clicking buttons, adding items to the cart, and checking that the UI updates correctly.

3) Navigation mode analyzes the page right after it loads and gives an overall report about the page's performance, accessibility, best practices, and SEO. Snapshot mode analyzes the page in its current state instead. Snapshot mode is more useful for checking accessibility issues on the current page, but it does not measure page load performance or JavaScript changes over time.

4) Based on the Lighthouse results, three things we could improve on the CSE 110 shop site are:

- Improve accessibility because the accessibility score was 90, so there may still be some elements that need better labels, alt text, or keyboard-friendly behavior.
- Improve best practices because that score was 81, which was the lowest score in the report. We could check the Lighthouse warnings and fix browser or security-related issues.
- Improve SEO because the SEO score was 91. We could add better metadata, such as a more descriptive title and meta description, so the page is easier for search engines to understand.