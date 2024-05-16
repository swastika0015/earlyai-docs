





# Getting started

## 1. Sample Project Setup

**Generate your first 20 unit tests using Early’s VSCode Extension**

This document will enable you to generate your first 20 unit tests in less than 5 minutes using Early's VSCode extension via a sample pre-configured TypeScript/Jest project.

**Sample Project setup:**
* Make sure you have [VSCode](https://code.visualstudio.com/download) Version 1.88 and later installed
* Clone Early's [sample-project](https://github.com/earlyai/sample-project) 
* Run the following command on the VSCode terminal:
```
npm install
```

*	Run Build On the NPM SCRIPTS tab on VSCode Explorer:
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


## 2. Install the Extension
**Install Early AI VSCode Extension via MSFT Marketplace:**

* Search for the **EarlyAI** extension on VSCode market place and install it
<figure>
    <img src="https://uploads-ssl.webflow.com/6583e7ad2ff3f8a81492938e/663f5c0353275a78f26c72b6_ExtensionMarketplace.png"
         alt="build the project" width=400 >
</figure>
<br>

* Open the extension and log in using the welcome-to-our-beta email information (ask to join our beta [here](https://www.startearly.ai/beta) if you don't have access)
<figure>
    <img src="https://uploads-ssl.webflow.com/6583e7ad2ff3f8a81492938e/663f5b7dd85cd43ed1487cb5_login.png"
         alt="build the project" width=400 >
</figure>
<br>

* More information about the EarlyAI extension can be found on Microsoft [Marketplace](https://marketplace.visualstudio.com/items?itemName=Early-ai.EarlyAI)

* We highly recommend that you also install the Jest extension, which  supports full [jest](https://jestjs.io/ "https://jestjs.io/") features in vscode environment to make testing more intuitive
<figure>
    <img src="https://uploads-ssl.webflow.com/6583e7ad2ff3f8a81492938e/663f5c0353275a78f26c72b6_ExtensionMarketplace.png"
         alt="build the project" width=400 >
</figure>
<br>


## 3. Run the Project

* 1. Click on Early Extension icon on the left bar
* 2. Click on the Coverage Refresh button
* 3. View the files and method tree on the project tree
<figure>
    <img src="https://uploads-ssl.webflow.com/6583e7ad2ff3f8a81492938e/663f5e1fc41f030d44eeb1c6_InitialSetup.png"
         alt="build the project" width=800 >
</figure>
<br>


 
## 4. Using the Extension

**Navigate through the extension views** 

 <span>1. </span> <img src="https://uploads-ssl.webflow.com/6583e7ad2ff3f8a81492938e/66465b7af49fee551912cb33_sample-project.png" width=100 />  <span>  A tree of all the testable methods /functions in the project</span>


<span>2. </span> <img src="https://uploads-ssl.webflow.com/6583e7ad2ff3f8a81492938e/663cb3694d4df63f692b4a2e_100percent.png" width=40 />  <span>   The percentage next to each method/function shows the code coverage of that method/function 
 </span>


<span>3. </span> <img src="https://uploads-ssl.webflow.com/6583e7ad2ff3f8a81492938e/663c7d2b6b8c8aabaa629b7f_Play.png" width=20 />  <span>   "Play" (generate tests) button next to public method names  
 </span>

<span>4. </span> <img src="https://uploads-ssl.webflow.com/6583e7ad2ff3f8a81492938e/663c7d2b7b9cc7555a5145ff_Refresh-botton.png" width=20 />  <span>  "Refresh" coverage button. Coverage refreshes automatically 10 idle seconds after unit tests generation </span>


![extension](https://uploads-ssl.webflow.com/6583e7ad2ff3f8a81492938e/66465c4834af6f45766befdb_extension.png)
<br>


 <span>5. </span> <img src="https://uploads-ssl.webflow.com/6583e7ad2ff3f8a81492938e/66465deb8f63471d9904c1cf_jesticon.png" width=20 />  <span>  Jest extension 
 </span>

* View and run all existing unit tests. green are passing and red

## 5. Generating your First Tests
**Generating unit tests for methods/functions**

There are two ways to generate unit tests

 <span>1. </span> <img src="https://uploads-ssl.webflow.com/6583e7ad2ff3f8a81492938e/663c7d2b6b8c8aabaa629b7f_Play.png" width=20 />  <span>  Play button via the code explorer, next to the public method/function name.  
 </span>

<span>2. </span> <img src="https://uploads-ssl.webflow.com/6583e7ad2ff3f8a81492938e/66465f70b6e51dd6844e5af7_GetOption.png" width=70 />  <span>  "Generate tests" Code lens above each public method/function name on the code editor.  
 </span>

Once you generate a test a VSCode notification bar will pop up on the bottom right corner until the generation is completed. Test generation can take between 15 to 30 seconds depending on the complexity of the code base and API response time.
![GeneratingTests](https://uploads-ssl.webflow.com/6583e7ad2ff3f8a81492938e/66465ec4bdaa85e0371cb669_GenerateTests.png)
<br> 



## 6. Review the coverage and generated tests 

**Now you are ready to generate tests for this entire sample project**

* After generating the tests the coverage would refreshed automatically
* Review the coverage on Early Extension

Currently we generate “Green” and “Red” unit tests.

* <span style="color: green;">Green</span> are healthy passing unit tests
* <span style="color: red;">Red</span> Red could be **good** tests that are revealing a bug or erroneous unit tests (bear with us as we improve the product).

* you can review the generated tests on the Jest extension or on any tool you use to execute Jest unit tests

![RefreshCoverage](https://uploads-ssl.webflow.com/6583e7ad2ff3f8a81492938e/66466296d7cabe8685fac2f4_Jestscreen.png)
<br>

## Known issues
* Sometimes a second login is required after refreshing the window on step 4.4
* While we are striving to 100% coverage (all test generation succeeded) sometimes our model likes to think outside the box, a bit too far outside... Early's fix in progress!!"
* for more information Check our [Github issues](https://github.com/earlyai/earlyai-vscode-release/issues) or the changelog on VSCode [Marketplace](https://marketplace.visualstudio.com/items?itemName=Early-ai.EarlyAI)

## What's Next:
Follow the [setup and configuration document](https://www.startearly.ai/elements/setup-and-configuration-guide) to setup your own projects and start generating meaningful unit tests for your code.

