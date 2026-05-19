1. Within a Github action that runs whenever code is pushed because it follows the practice of continuous integration. It catches bugs right away so if something were to break after a push, you would know exactly what and when. Additionally, it is automated which eliminates human inconsistencies such as forgetting or being lazy to run tests on changes that could still be broken no matter how small. Lastly, running it through Github Actions tests in a clean, isolated environment so tests will pass not just on your machine, but be able to pass on others as well.
2. You would use a unit test instead of an end to end test to check if a function is returning the correct output. If you were just checking the output of one function which is just one piece of a program, a unit test would be more appropriate since there is no need to test the whole program flow when just focusing on one function.





