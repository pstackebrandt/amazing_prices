# Amazing Prices

## Description

My project contains code of a training project for the course 'Frontend Core' by hyperskill.org .
https://hyperskill.org/projects/309
Amazing Prices

My project doesn't contain the code created by hyperskill for managing a hyperskill training project.

My code is not finished. This project contains my solution for stage 1.
HyperSkills test #4 for this stage seems to be broken. I have passed test 3 only.

I get this error message for test 4:

"Error: Wrong answer in test #4

In the page, the element with the selector of header's border-bottom is different from the Figma designs or the description.

    at Test._runTests (node_modules\hs-test-web\dist\hstest\stage\stageTest.js:74:19)
    at process.processTicksAndRejections (node:internal/process/task_queues:95:5)
    at async Test.runTests (node_modules\hs-test-web\dist\hstest\stage\stageTest.js:28:9)
    at async Context.<anonymous> (file:///C:/Users/peter/code/javascript/Amazing%20Prices/Amazing%20Prices/task/test/test.js:288:5)
"

The test.js of hyperskill contains this comment on line 199: // test #4 removed
That is strange.

This test #4 contains the following lines:

// check if header has correct border-bottom
if (this.checkBorder(this.header))
    return wrong(this.wrongStyleMsg(this.header, "border-bottom"));

// check if footer has correct border-top
if (this.checkBorder(this.footer, "top"))
    return wrong(this.wrongStyleMsg(this.footer, "border-top"));

This test seems to check whether the header has set border-bottom and the footer has set border-top.

My css declares the required properties. So the test code seems to be broken.
A couple of comments https://hyperskill.org/projects/309/stages/1731/implement#comment regarding test 4 by different
users from different months confirm this.

It may be that this test works for a couple of people.  "48 users solved this stage. Latest completion was 2 weeks ago.
" But it's a small number of people who finished that simple first stage. 

 