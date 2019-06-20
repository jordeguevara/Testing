### Testing Guide

## Current Testing Tools 
a) super-test 

- used for testing behavior of controllers, typically for integration testing

b) sinon 
 
 - used to check behavior of different functions with spies,stubs, and mocks

c) mocha 

- testing framework used by node.js, allows you to a layer of abstraction over vanilla node.js assertions 

d) chai 

- allows to us to utilize semantic, declartive methods to make testing more readable 


<b>Manaul Testing</b>  - Postman 

<i>Upload manual test to Postman and work with Niko to share with the rest on the team </i>


## Styling Guide 
Unit Testing

naming convention - name the it as unit_test ie (businessLogic_unit_test.js) 
test/controllers/policy/index_test.js -Integration Test

Integratation Test 

naming convention - name the it as myfile_test ie (index_unit_test.js) 

Add any custom objects in the fixture directory (test/fixtures)

### Workflow 


### Types of Testing
System Integration - end to end test of the architecture  

Intergnal integration test - <i> tests the behavior of several functions interacting together </i>

Unit test - <i> automated tests that ensure that a section of an application meets its design and behaves as intended <i>
* business logic 
* calander math
* complicated logic 

### Tips 
We should explict names for the the api end routes (ex '/myRoute')

Develop great documentettion for our APIs, can be automated with postman testing suite 

Dont use version number in the name of the endpoint, unless no other choice 

We should group similar endpoints together 

### ES-LINT - TBD
<i>There is currently a preconfigured ESLint File in MBE, so all you have to do is download an ESLinter and turn off any other extensions that may override it </i>
## Test Coverage 

To see a detail report of test coverage run: 
```
npm run test-with-coverage
```

in root directory, there will be a folder called coverage, look for an index.html and open it with the browser

This will show detailed view of test coverage 

We aim to get at least <b>80%</b> test coverage for features that you are working on 

### Links to Documentation 

[SuperTest](https://www.npmjs.com/package/supertest)

[Mocha](https://mochajs.org/)

[Chai](https://www.chaijs.com/api/bdd/)

[Sinon](https://sinonjs.org/releases/latest/)

