# Class 02 Reading Notes

**Intro to NodeJS and Express**  
1\. Middleware are just the functions that deal witht the requests being passed in from the front in and sending responses  
2\. Node web framework  
3\. It means it has less rules (restrictions) on how to make it do what you want in to do, so it's more flexible at solving various problems outside its regular scope  
4\. A module is code you can use inside another file by using require(), this is useful for devs because it allows us to split different tasks/roles up into different files and name them based on what they do, making our code a lot neater, easier to read  

**What is NPM**  
1\. 9.2.0  
2\. npm i jshint  

**What is TDD**  
1\. Because it allows us to make sure our code is 1: running how it is supposed to (especially before deploying said code, which makes the coding process quicker/more efficient) and 2: running optimally as well as understandable (which is great if someone else is reading your code as well as duplicability)  
2\. reductions in defective code, a reduction in effort in a project's final phases, improved design qualities in the code  
3\. Individual: not enough and/or too many tests all at once  
Team: not everyone on board using TDD and/or poor maintenance of the test suite  

**CI/CD**  
1\. see if everyones code works together, see which code works best, see these test run and pass/fail in real time  
2\. Cdeploymnet is all about getting the deployment out sooner and then bug fixes, vs Cdelivery tries to weed out the bugs beforehand  
3\. gitHub allows us to make branches and we can decide to deploy from any branch we want, as well as if we decide to only deploy from main then we can still know how our code is doing on another branch by running our code locally on said branch and then if its all good we can push to main for the deployment to change  
