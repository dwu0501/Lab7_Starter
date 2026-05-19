##  Members:
- Daniel Wu

## "Check Your Understanding" Questions:
1. Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

Within a Github action that runs whenever code is pushed. While manually running tests before pushing code can be a good practice in order to reduce the overhead given by GitHub actions, having Github actions setup is essential to check the integrity of the code at all times and reduce human error (which could happen if wen run tests locally) by guaranteeing that tests are ran after every push.

2. Would you use an end to end test to check if a function is returning the correct output?

Yes.

3. What is the difference between navigation and snapshot mode?

While navigation mode takes a snapshot of the page on load, without taking into account user interaction (ensures the base performance), snapshot mode takes into account the current state of the website and analyzes it (meassures performance while/after user interaction) to make sure that the page works correctly even after the user interacts with it.

4. Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results

- Define the language we are using in HTML
- Include meta descriptions in order for search engines to correctly summarize the page content
- Improve latency of the critical path, avoid chaining many paths together to avoid downloading unnecessary assets.



