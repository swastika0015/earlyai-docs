# Getting started

## 1. Sample Project Setup

**Generate your first 30 unit tests using Early’s VSCode Extension**

This document will enable you to generate your first 30 unit tests in less than a minute minutes using Early's VSCode extension via a sample earlyai-todo-app pre-configured TypeScript/Jest project.

**earlyai-todo-app project setup:**
* Make sure you have [VSCode](https://code.visualstudio.com/download) Version 1.88 and later installed
* Clone Early's [earlyai-todo-app](https://github.com/earlyai/earlyai-todo-app) 
* Run the following command on the VSCode terminal:
```
npm install
```
* process should be completed sussessfule with 0 vulnerabilities found. 

> The sample project Setup is completed
<br>


## 2. Install the Extension
**Install Early AI VSCode Extension via MSFT Marketplace:**

* Search for the **EarlyAI** extension on VSCode market place and install it
<figure>
    <img src="https://raw.githubusercontent.com/babybeluga1980/documentation/main/media/extension-marketplace.png"
         alt="marketplace" width=400 >
</figure>
<br>

* Open the extension and log in using your mail address for verification
<figure>
    <img src="https://raw.githubusercontent.com/babybeluga1980/documentation/main/media/Signin.png" alt="signin" width=400 >
</figure>
<br>

* More information about the EarlyAI extension can be found on Microsoft [Marketplace](https://marketplace.visualstudio.com/items?itemName=Early-ai.EarlyAI)

* We highly recommend that you also install the Jest extension, which  supports full [jest](https://jestjs.io/ "https://jestjs.io/") features in vscode environment to make testing more intuitive
<figure>
    <img src="https://uploads-ssl.webflow.com/6583e7ad2ff3f8a81492938e/66466550cfe7ddcd60a65d88_Jest-extension.png" width=400 >
</figure>
<br>


## 3. Browse the extension

* 1. Click on Early Extension icon on the left bar
* 2. Make sure your project has node_modules, jest.config, and jest setup correctly
* 3. View the files and method tree on the project tree
<figure>
    <img src="https://raw.githubusercontent.com/babybeluga1980/documentation/main/media/extension-setup.png"
         alt="build the project" width=400 >
</figure>
<br>

 
## 4. Using the Extension

**Navigate through the extension views** 

 <span>1. </span> <img src="https://raw.githubusercontent.com/babybeluga1980/documentation/main/media/Icon-testablecode.png" width=100 />  <span>  A tree of all the testable methods /functions in the project</span>


<span>2. </span> <img src="https://raw.githubusercontent.com/babybeluga1980/documentation/main/media/Icon-100.png" width=40 />  <span>   The percentage next to each method/function shows the code coverage of that method/function 
 </span>


<span>3. </span> <img src="https://raw.githubusercontent.com/babybeluga1980/documentation/main/media/icon-generatetests.png" width=20 />  <span>   "Play" (generate tests) button next to public method names  
 </span>

<span>4. </span> <img src="https://raw.githubusercontent.com/babybeluga1980/documentation/main/media/icon-gototests.png" width=20 />  <span>  "Go-to tests" go to the unit tests file that was generated </span>

<span>5. </span> <img src="https://raw.githubusercontent.com/babybeluga1980/documentation/main/media/Icon-codelens.png" width=200 />  <span>  code lens above public method/function names </span>

<span>6. </span> <img src="https://raw.githubusercontent.com/babybeluga1980/documentation/main/media/icon-refresh.png" width=20 />  <span>  "Refresh" coverage button. note: Coverage refreshes automatically after test geneartions</span>


![extension](https://raw.githubusercontent.com/babybeluga1980/documentation/main/media/extension-overview.png)
<br>



## 5. Generating your First Tests
**Generating unit tests for methods/functions**

There are three ways to generate unit tests

<span>1. </span> <img src="https://raw.githubusercontent.com/babybeluga1980/documentation/main/media/icon-generatetests.png" width=20 />  <span>  Play button via the code explorer, next to the public method/function name.  
 </span>

<span>2. </span> <img src="https://raw.githubusercontent.com/babybeluga1980/documentation/main/media/icon-codelens-gentest.png" width=140 />  <span>  "Early AI: Generate tests" Code lens above each public method/function name on the code editor.  
 </span>

<span>3. </span> <img src="https://raw.githubusercontent.com/babybeluga1980/documentation/main/media/icon-contextmenu-gentests.png" width=140 />  <span>  context menu: right click within a method name or scope  
 </span>
Once you generate a test a VSCode notification bar will pop up on the bottom right corner until the generation is completed. Test generation can take between 15 to 30 seconds depending on the complexity of the code base and API response time.

![GeneratingTests](https://raw.githubusercontent.com/babybeluga1980/documentation/main/media/screen-generatingtests.png)
<br> 

## 6. Review the generated tests 

**Now you are ready to view the tests generated and respective coverage**

* After generating the tests the coverage would refreshed automatically
* Review the tests and respective coverage on Early Extension

EarlyAI generate complex tests that includes mocks, logic, happy path and edge cases. We also  generate “Green” and “Red” unit tests.

* <span style="color: green;">Green</span> are healthy passing unit tests
* <span style="color: red;">Red</span> Red could be **good** tests that are revealing a bug or erroneous unit tests (bear with us as we improve the product).

You can go-to the generated tests and view them in 3 ways.

<span>1. </span> <img src="https://raw.githubusercontent.com/babybeluga1980/documentation/main/media/icon-gototests.png" width=20 />  <span>  "Go-to tests" go to tests button next to the method name </span>


<span>2. </span> <img src="https://raw.githubusercontent.com/babybeluga1980/documentation/main/media/icon-codelens-gototests.png" width=140 />  <span>  "Early AI: go to tests" Code lens above each public method/function name on the code editor.  
 </span>

<span>3. </span> <img src="https://raw.githubusercontent.com/babybeluga1980/documentation/main/media/icon-contextmenu-gototests.png" width=140 />  <span>  context menu: right click within a method name or scope  
 </span>

![ViewTests](https://raw.githubusercontent.com/babybeluga1980/documentation/main/media/Screen-viewtests.png)
<br>

Run your tests via your preferred jest runner (command line or Jest extension) to view and troubleshoot the various tests.
## Known issues
* While we are striving to 100% coverage (all test generation succeeded) sometimes our model likes to think outside the box, a bit too far outside... we will still show you the results, they could be impressive.
* for more information Check our [Github issues](https://github.com/earlyai/earlyai-vscode-release/issues) or the changelog on VSCode [Marketplace](https://marketplace.visualstudio.com/items?itemName=Early-ai.EarlyAI)

## What's Next
Follow the [setup and configuration document](https://www.startearly.ai/elements/setup-and-configuration-guide) to setup your own projects and start generating meaningful unit tests for your code.

