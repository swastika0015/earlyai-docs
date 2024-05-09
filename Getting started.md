


# Getting started

## Step 1 - Sample project setup
**Generating your first 20 unit tests using Early’s VSCode Extension**

This document will enable you to generate your first 20 unit tests in less than 5 minutes using Early's VSCode extension via a sample pre-configured TypeScript/Jest project.

Sample Project setup
* Clone early [sample-project](https://github.com/earlyai/sample-project) 
* Run the following command on the VSCode terminal:
```
npm install
```

*	On the NPM SCRIPTS tab on VSCode Explorer
```
Run Build
```
<figure>
    <img src="https://uploads-ssl.webflow.com/6583e7ad2ff3f8a81492938e/663be67189425152535939b4_npmscript.png"
         alt="build the project" width=400 >
</figure>

* You should get the message 
```webpack 5.90.1 compiled successfully in xxx ms```
<figure>
<img src="https://uploads-ssl.webflow.com/6583e7ad2ff3f8a81492938e/663be67125f8f71f7cdb2aad_buildnest.png" alt="build the project" width=400 >
</figure>

> The sample project Setup is completed

<br>


## Step 2 - Install the extension
**Install Early AI VSCode Extension via MSFT market-Place**

First, Search and install for the **Early AI** extension and log-in to your account
* Search for the extension on VSCode market place and install it
* Open the extension and log in using the welcome to our beta email information (ask to join our bete [here](https://www.startearly.ai/beta) if you don't have access)
<figure>
    <img src="https://uploads-ssl.webflow.com/6583e7ad2ff3f8a81492938e/663c6ec6c27fae3ce11aec89_Market%20place.png"
         alt="build the project" width=400 >
</figure>
<br>

## Step 3 - Run the project

* Click on Early Extension icon on the left bar
* Run the tests – verify they are green (if not go back to [Sample Project Setup](##Step-1---Sample-project-setup) )
* Click on the Coverage Refresh button
* Reload Window (>Developer: Reload Window)
<figure>
    <img src="https://uploads-ssl.webflow.com/6583e7ad2ff3f8a81492938e/663cb10312e36b9357f338a2_RefreshCoverage.png"
         alt="build the project" width=800 >
</figure>
<br>


 
## Step 4 - Using the extension

**Navigate through the extension views** 

 <span>1. </span> <img src="https://uploads-ssl.webflow.com/6583e7ad2ff3f8a81492938e/663c7e0c461b99a8e3ccaea1_Code%20Explorer.png" width=100 />  <span>  A tree of all the testable methods 
 </span>
 * Shows all testable (public) methods and/or functions in the project 


<span>2. </span> <img src="https://uploads-ssl.webflow.com/6583e7ad2ff3f8a81492938e/663cb3694d4df63f692b4a2e_100percent.png" width=40 />  <span>   The percentage next to each method/function shows the code coverage of that method/function 
 </span>


<span>3. </span> <img src="https://uploads-ssl.webflow.com/6583e7ad2ff3f8a81492938e/663c7d2b6b8c8aabaa629b7f_Play.png" width=20 />  <span>   "Play" (generate tests) button next to public method names  
 </span>

<span>4. </span> <img src="https://uploads-ssl.webflow.com/6583e7ad2ff3f8a81492938e/663c7d2b7b9cc7555a5145ff_Refresh-botton.png" width=20 />  <span>  "Refresh" coverage button – next to the project name. </span>

 <span>5. </span> <img src="https://uploads-ssl.webflow.com/6583e7ad2ff3f8a81492938e/663c7e0c6d75744c585e6dc1_Test%20Explorer.png" width=100 />  <span>  A tree of  all the existing unit tests in the project. 
 </span>


* Clicking the “play” button on the text explorer tree executes all tests below that level.
* Note that there is one sample unit tests under ****src/sample.test.ts****. this is required for the initialization of the extension. 

![extension](https://uploads-ssl.webflow.com/6583e7ad2ff3f8a81492938e/663c87d9cdcc01126dc9fcf7_Extension.png)
<br>



## Step 5 - Generating your first tests
**Generating unit tests for methods/functions**
*There are two ways to generate unit tests*
<span>1. </span> <img src="https://uploads-ssl.webflow.com/6583e7ad2ff3f8a81492938e/663c7d2b6b8c8aabaa629b7f_Play.png" width=20 />  <span>   Play button via the code explorer, next to the public method/function name.  
 </span>

<span>2. </span> <img src="https://uploads-ssl.webflow.com/6583e7ad2ff3f8a81492938e/663cb680268c302f4e39b758_GenerateTest1.png" width=100 />  <span>  "Generate tests" Code lens above each public method/function name on the code editor.  
 </span>

Once you generate a test a VSCode notification bar will pop up on the bottom right corner until the generation is completed. Test generation can take anyways from 20 to 60 seconds depending on the complexity of the code base and API response time.
![GeneratingTests](https://uploads-ssl.webflow.com/6583e7ad2ff3f8a81492938e/663c87d8cdcc01126dc9fcdb_GenerateTests.png)
<br> 



## Step 6 -  Generate and refreshing Coverage 
**Now you are ready to generate tests for this entire sample project**

* Click on each public method
* Refresh the coverage once the generation is completed
* Review the test generated and their respective code coverage.

Currently we generate “Green” and “Red” unit tests.

Green are healthy passing unit tests

Red could be “good” tests that are revealing a bug or erroneous unit tests (bear with us until we improve the product).
![RefreshCoverage](https://uploads-ssl.webflow.com/6583e7ad2ff3f8a81492938e/663c87d85829aad6b012e157_RefreshCoverage.png)
<br>


## What's Next:
Follow the [setup and configuration document](https://www.startearly.ai/elements/setup-and-configuration-guide) to setup your own projects and start generating meaningful unit tests for your code.

