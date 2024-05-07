# Getting started

**Generating your first 20 unit tests using Early’s VSCode Extension**

This document will enable you generating your first 20 unit tests in less then 5 min using early AI’s VSCode extension via a sample pre-configured typescript/jest project.

Sample Project setup
* Clone project: https://github.com/earlyai/sample-project-microservices 
* Run the following command on the VSCode terminal:
```
npm install
```

*	on the NPM SCRIPTS tab on VSCode Explorer
```
Run Build
```
[Link to image]
* You should get the message 
```webpack 5.90.1 compiled successfully in xxx ms”```

>The sample project Setup is completed

## Install Early AI VSCode Extension via MSFT market-Place

First, Search and install the Early AI extension and log-in to your account

* Click on Early Extension icon on the left bar
* Run the tests – verify they are green (if not go back to project setup stage)
* Click on the Coverage Refresh button
* Reload Window (>Developer: Reload Window)

[Image here]
Early AI Extension – initial setup

 
## Post initial Early’s extension setup:
**Browse the extension screens** 
1.	  [Code explorer image here] Tree of all the testable methods
* Shows all testable (public) methods in the project 
* Next to each method it shows the code coverage of the unit tests that testing that method.
* [button image here] “Play button” – next to public method names – generate unit tests 
* [refresh image here] “Refresh” coverage button – next to the project name


2.	 [test explorer image here] Shows all the existing unit tests in the project. 
o	Clicking on the “play” button next to each level of that tree executes all tests below that level.
o	Note that there is one sample unit tests under apps/test/sample.early.test.ts. this is required for the initial work of the extension. 

[Image here]
Early AI Extension

**Generating unit tests for methods**
*There are two ways to generate unit tests*
* [play button image here] Play button via the code explorer, next to the public method name.
* [Generate test image here]  Code lens above each public method name on the code viewer

Once you generate a test a VSCode notification bar will pop up on the bottom right corner until the generation is completed. Test generation can take anyways from 20-60 seconds depends on the complexity of the code base and API response time.
[Insert image here]
Generating tests
 
 ## Generate and refresh the code Coverage ##
**Now you are ready to generate tests for this entire sample project**

* Click on each public method
* Refresh the coverage once the generation is completed
* Review the test generated.

Currently we generate “Green” and “Red” unit tests.

Green are healthy passing unit tests

Red could be erroneous unit tests (bare with us until we improve the product) OR “good” tests that are revealing a bug.
[Insert image here]
Refreshing coverage

## Next: ## 
Follow the setup and configuration document to setup your own projects and start generating meaningful unit tests for your code.
