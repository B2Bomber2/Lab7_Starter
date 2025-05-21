1. Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

- [ x ] Within a Github action that runs whenever code is pushed 
- [ ] Manually run them locally before pushing code
- [ ] Run them all after all development is completed

You should manually run tests to make sure you are not missing anything or pushing buggy code. However, automated tests shoud be placed in a yml file on GitHub actions. The automated test make sure that what you pushed is bug free. If it is not bug free, you should go back and fix it before pushing again. It should check everytime there is a push because you want to make sure that the new updates are tested. The automated tests also help others when they review your code and pull request. 

2. Would you use an end to end test to check if a function is returning the correct output? (yes/no)
no 

3. What is the difference between navigation and snapshot mode?

Navigation is used to record the performance of a full page load. So, the time the URL is requested to when everything finishes loading is recorded. Snapshot is is used to record the performance from a specific moment in time without navigating away from the current page. 

4. Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.
- The site could improve its accessibility by including the lang attribute in its HTML. 
- The site could improve its accessibility by also using font sizes legible for mobile devices and for people with poor vision. 
- Since the site is a shop, it should improve its search engine optimization to bring in more customers. There should be meta tags and descriptions in its HTML. 