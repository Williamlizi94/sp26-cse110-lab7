# Lab 7

## Check Your Understanding

1) I would choose **Option 1: Within a GitHub Action that runs whenever code is pushed**.

I think this is the best option because it makes testing part of the normal development pipeline instead of something I have to remember to do manually. If a new change breaks the Recipe project, the tests can catch the problem right away before the broken code gets merged or deployed. Manually running tests locally is still helpful, but it is easier to forget. Waiting until all development is completed is also too late because bugs would be harder to find and fix.

2) No, I would not use an end-to-end test just to check if a function is returning the correct output. That is better suited for a unit test because it focuses on one small function directly. End-to-end tests are better for testing a full user flow, like loading the page, clicking buttons, adding items to the cart, and checking that the UI updates correctly.