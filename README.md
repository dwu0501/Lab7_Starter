##  Members:
- Daniel Wu

## "Check Your Understanding" Questions:
1. Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

Within a Github action that runs whenever code is pushed. While manually running tests before pushing code can be a good practice in order to reduce the overhead given by GitHub actions, having Github actions setup is essential to check the integrity of the code at all times and reduce human error (which could happen if we run tests locally) by guaranteeing that tests are ran after every push.

2. Would you use an end to end test to check if a function is returning the correct output?

No, to check the behaviour of specific functions I'd use unit tests since they are faster and you can test much more thoroughly each function. E2E testing is to check the general operation of the application.

3. What is the difference between navigation and snapshot mode?

While navigation mode analyses the page right after it loads and gives performance metrics for this initial load, without taking into account user interaction; snapshot mode analyses the page after user interaction which helps test accessibility issues, but it does not analyze JS performance or DOM changes over time.


4. Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results

- Define the language we are using in HTML
- Include meta descriptions in order for search engines to correctly summarize the page content
- Improve latency of the critical path, avoid chaining many paths together to avoid downloading unnecessary assets.



