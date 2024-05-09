
# Getting started

## Step 1 - Sample project setup
**Generating your first 20 unit tests using Early’s VSCode Extension**

This document will enable you generating your first 20 unit tests in less then 5 min using early AI’s VSCode extension via a sample pre-configured typescript/jest project.

Sample Project setup
* Clone project: https://github.com/earlyai/sample-project 
* Run the following command on the VSCode terminal:
```
npm install
```

*	on the NPM SCRIPTS tab on VSCode Explorer
```
Run Build
```
<figure>
    <img src="https://uploads-ssl.webflow.com/6583e7ad2ff3f8a81492938e/663be67189425152535939b4_npmscript.png"
         alt="build the project" width=400 >
</figure>
* You should get the message 
```webpack 5.90.1 compiled successfully in xxx ms”```
<figure>
<img src="https://uploads-ssl.webflow.com/6583e7ad2ff3f8a81492938e/663be67125f8f71f7cdb2aad_buildnest.png" alt="build the project" width=400 >
</figure>

> The sample project Setup is completed

## Step 2 - Install the extension
**Install Early AI VSCode Extension via MSFT market-Place**

First, Search and install the Early AI extension and log-in to your account
* Search for the extension on VSCode market place and install it
* Open the extension and log in using the welcome to our beta email information (you will need access to your email for firebase authentication)


## Step 3 - Run the project

* Click on Early Extension icon on the left bar
* Run the tests – verify they are green (if not go back to project setup stage)
* Click on the Coverage Refresh button
* Reload Window (>Developer: Reload Window)
<figure>
    <img src="https://uploads-ssl.webflow.com/6583e7ad2ff3f8a81492938e/663be671b200d5941d97168b_initialSetup.png"
         alt="build the project" width=800 >
</figure>

Early AI Extension – initial setup

 
## Step 4 - Using the extension

**Browse the extension screens** 
1.	  *CODE EXPLORER* Tree of all the testable methods
* Shows all testable (public) methods in the project 
* Next to each method it shows the code coverage of the unit tests that testing that method.
* “Play button” – next to public method names – generate unit tests 
* “Refresh” coverage button – next to the project name


2.	 [test explorer image here] Shows all the existing unit tests in the project. 
o	Clicking on the “play” button next to each level of that tree executes all tests below that level.
o	Note that there is one sample unit tests under apps/test/sample.early.test.ts. this is required for the initial work of the extension. 

![extension](https://uploads-ssl.webflow.com/6583e7ad2ff3f8a81492938e/663be672d69d5cabd86f1081_Extension.png)
Early AI Extension

## Step 5 - Generating your first tests
**Generating unit tests for methods**
*There are two ways to generate unit tests*
* [play button image here] Play button via the code explorer, next to the public method name.
* [Generate test image here]  Code lens above each public method name on the code viewer

Once you generate a test a VSCode notification bar will pop up on the bottom right corner until the generation is completed. Test generation can take anyways from 20-60 seconds depends on the complexity of the code base and API response time.
![GeneratingTests](https://uploads-ssl.webflow.com/6583e7ad2ff3f8a81492938e/663be671f91da71e57b6c8aa_GenerateTests.png)
Generating tests
 
 ## Generate and refresh the code Coverage 
**Now you are ready to generate tests for this entire sample project**

* Click on each public method
* Refresh the coverage once the generation is completed
* Review the test generated.

Currently we generate “Green” and “Red” unit tests.

Green are healthy passing unit tests

Red could be erroneous unit tests (bare with us until we improve the product) OR “good” tests that are revealing a bug.
![RefreshCoverage](https://uploads-ssl.webflow.com/6583e7ad2ff3f8a81492938e/663be6711082e0f1590fd508_RefreshCoverage.png)
Refreshing coverage

## What's next Next:
Follow the setup and configuration document to setup your own projects and start generating meaningful unit tests for your code.

