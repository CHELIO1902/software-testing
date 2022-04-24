# Software Testing Fundamentals

Here you will find fundamentals of modern testing, testing from tester's and developer's
perspective, tips, techniques, strategies to do software testing, and more :]

This will definitely improve your software's quality.

### Index
-   [Intro](#intro)
-   [Black Box Testing](#Black-Box-Testing)
-   [White Box Testing](#White-Box-Testing)
-   [Black Box Testing vs White Box Testing](#Black-Box-Testing-vs-White-Box-Testing)


## Intro

The main reason why many users quit from using a certain software, it's because its
performance is slow, buggy, does not work on certain devices, and so on.

Testing software is just as important as developing it. In order to deliever a great UX,
make sure everything works, scale, we need to test our software.

But first, let's talk about Black Box Testing and White Box Testing.

**[⬆ Back to Index](#index)**


## Black Box Testing

Black Box Testing is a method in which the functionalities are tested without knowing
what the internal code structure, implementation details & internal paths are.

It focuses mainly on input and output of software. It is entirely based on the product
requirements and specifications.

Black Box Testing is also known as *Behavioral Testing*.

![assets/blackbox.webp](assets/blackbox.webp)


**How to do Black Box Testing**

1. Examination of the system requirements and specifications.
2. Tester chooses valid inpusts (as in a positive test scenario/use case) to
   check whether Software Under Test(SUT) processes them correctly.
3. Tester chooses invalid inputs (as in a negative test scenario/case) are chosen
   to verify that the SUT is able to detect them.
4. Tester determines expected outputs for the tested inputs.
5. Software tester constructs test cases with the selected inputs.
6. The test cases are executed.
7. Testers compares actual outputs with the expected outs.
8. Defects if any are fixed and software is re-tested.


**Types of Black Box Testing**

- Function Testing: This testing is related to the functional requirements of a 
  system; it is done by software testers.
- Non-functional Testing: This testing is related to requirements such as performance,
  scalability, usability.
- Regression Testing: This testing is done after code fixes, upgrades or any other
  system maintenance to check the new code hasn't affected the existing code.


**Black Box Testing Tools**

- Fo Functional|Regression Testing: QTP, Selenium.
- For Non-functional Testing: LoadRUnner, Jmeter.


**Black Box Testing Techniques**

- *Equivalence Class Testing*: It's used to minimize the number of possible test cases to
  an optimum level whilte maintaining reasonable testing coverage.
- *Boundary Value Testing*: It's focused on the values at boundaries. This technique
  determines whether a certain range of values are acceptable by the system or not.
- *Decision Table Testing*: A decision table puts causes and their effects in a matrix.
  There is a unique combination in each column.

**Black Box Testing and Software Development Life Cycle(SDLC)**

Black Box Testing has its own life cycle called Software Testing Life Cycle (STLC), and
it's relative to every stage of SDLC of Software Engineering.

1. Requirement: SDLC initial stage where requirements are gathered. Testers take part here.
2. Test Planning & Analysis: Testing Types applicable to the project are determined. A Test
   Plan is created in which possible risks and their mitigations are determined.
3. Design: Test cases/scripts are created based on requirement documents.
4. Testing Execution: Test Cases are executed. Bugs if any are fixed and re-tested.

**[⬆ Back to Index](#index)**


## White Box Testing

White Box Testing is a method in which internal structure, design and coding of software 
are tested to verify flow of input-output and to improve design, usability and security.

In White Box Testing, code is visible to testers so it is also called "Clear box testing",
"Open box testing", "Transparent box testing", "Code-based testing" and "Glass box testing".

This is one of two parts of the Box Testing approach to software testing. Its counterpart
Black Box Texting, involves testing from an external or end-user-type perspective.

On the other hand, White Box Testing in software engineering is based on the inner workings
of an application and revolves around internal testing.

![assets/blackbox.webp](assets/whitebox.webp)

"White Box" name symbolizes the ability to see through the software's outter shell (or "box").
While "Black Box" symbolizes not being able to see the inner structures, so that only the
end-user experience can be tested.

**What do you verify in White Box Testing?**
-  Internal security holes.
-  Broken or poorly structured paths in the coding processes.
-  The flow of specific inputs through the code.
-  Expected output.
-  The functionality of conditional loops.
-  Testing of each statement, object, and function on an individual basis.

White Box Testing can be done at system, integration and unit levels of software development. One of
the basic goals of White Box Testing is to veirfy a working flow for an app. 

It involves testing a series of predefined inputs against expected or desired outputs,
so that when a specific input does not result in the expected output, you have found a bug.

**Types of White Box Testing**

-  Unit Testing: It is often the first type of testing done on an app. Unit Testing is
   performed on each unit or block of code as it is developed. It is used done by the programmer.
   As a software developer, you develop a few lines of code, a single function or an object and test
   it to make sure it works before continuing Unit Testing helps identify a majority of bugs, early
   in the software development lifecycle. Bugs identified in this stage are cheaper and easy to fix.

-  Testing for Memory Leaks: Memory leaks are leading causes of slower running applications. A QA
   specialist who is experienced at detecting memory leaks is essential in cases where you have a
   slow running software application.

**Types of White Box and Black Box Testing (shared types of testing)**

-  White Box Penetration Testing: In this testing, the tester/developer has full information of the
   application’s source code, detailed network information, IP addresses involved and all server information
   the application runs on.  The aim is to attack the code from several angles to expose security threats.

-  White Box Mutation Testing: Mutation testing is often used to discover the best coding techniques 
   to use for expanding a software solution.


**White Box Testing Tools**

- Parasoft Jtest
- EclEmma
- NUnit
- PyUnit
- HTMLUnit
- CppUnit


**Advantages of White Box Testing**
-  Code optimization by finding hidden errors.
-  White box tests cases can be easily automated.
-  Testing is more thorough as all code paths are usually covered.
-  Testing can start early in Software Development Life Cycle (SDLC) even if the
   Graphic User Interface (GUI) is not available.


**Disadvantages of WhiteBox Testing**
-  It can be quite complex, time-consuming and expensive (depending on the App).
-  If the white box testing by developers is not detailed, it can lead to production errors.
-  It requires professional resources and a detailed understanding of programming and implementation.

**Ending Notes**
-  White Box Testing can be quite complet depending on the app being tested. It could take from a couple
   days, to weeks in order to be fully tested.
-  It should be done on a software app as it is being developed after it is written & again after each
   modification.

## Black Box Testing vs White Box Testing

*in case you didn't read the topics above, here's a summary of BBT & WBT*

**What is Black Box Testing?**

In Black-box testing, a tester doesn’t have any information about the internal working of the software system.
Black box testing is a high level of testing that focuses on the behavior of the software. It involves testing 
from an external or end-user perspective. Black box testing can be applied to virtually every level of 
software testing: unit, integration, system, and acceptance.

**What is White Box Testing?**

White-box testing is a testing technique which checks the internal functioning of the system. In this method,
testing is based on coverage of code statements, branches, paths or conditions. White-Box testing is considered
as low-level testing. It is also called glass box, transparent box, clear box or code base testing. 
The white-box Testing method assumes that the path of the logic in a unit or program is known.

**Black Box Testing and White Box Testing Differences**

<table>
  <thead>
    <tr>
      <th></th>
      <th>Black Box Testing</th>
      <th>White Box Testing</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <strong>Definition</strong>
      </td>
      <td>It is a testing approach which is used to test the software without the knowledge of the internal structure of program or application.</td>
      <td>It is a testing approach in which internal structure is known to the tester.</td>
    </tr>
    <tr>
      <td>
        <strong>Alias</strong>
      </td>
      <td>It also knowns as data-driven, box testing, data-, and functional testing.</td>
      <td>It is also called structural testing, clear box testing, code-based testing, or glass box testing.</td>
    </tr>
    <tr>
      <td>
        <strong>Base of Testing</strong>
      </td>
      <td>Testing is based on external expectations; internal behavior of the application is unknown.</td>
      <td>Internal working is known, and the tester can test accordingly.</td>
    </tr>
    <tr>
      <td>
        <strong>Usage</strong>
      </td>
      <td>This type of testing is ideal for higher levels of testing like System Testing, Acceptance testing.</td>
      <td>Testing is best suited for a lower level of testing like Unit Testing, Integration testing.</td>
    </tr>
    <tr>
      <td>
        <strong>Programming knowledge</strong>
      </td>
      <td>Programming knowledge is not needed to perform Black Box testing.</td>
      <td>Programming knowledge is required to perform White Box testing.</td>
    </tr>
    <tr>
      <td>
        <strong>Implementation knowledge</strong>
      </td>
      <td>Implementation knowledge is not requiring doing Black Box testing.</td>
      <td>Complete understanding needs to implement WhiteBox testing.</td>
    </tr>
    <tr>
      <td>
        <strong>Automation</strong>
      </td>
      <td>Test and programmer are dependent on each other, so it is tough to automate.</td>
      <td>White Box testing is easy to automate.</td>
    </tr>
    <tr>
      <td>
        <strong>Objective</strong>
      </td>
      <td>The main objective of this testing is to check what functionality of the system under test.</td>
      <td>The main objective of White Box testing is done to check the quality of the code.</td>
    </tr>
    <tr>
      <td>
        <strong>Basis for test cases</strong>
      </td>
      <td>Testing can start after preparing requirement specification document.</td>
      <td>Testing can start after preparing for Detail design document.</td>
    </tr>
    <tr>
      <td>
        <strong>Tested by</strong>
      </td>
      <td>Performed by the end user, developer, and tester.</td>
      <td>Usually done by tester and developers.</td>
    </tr>
    <tr>
      <td>
        <strong>Granularity</strong>
      </td>
      <td>Granularity is low.</td>
      <td>Granularity is high.</td>
    </tr>
    <tr>
      <td>
        <strong>Testing method</strong>
      </td>
      <td>It is based on trial and error method.</td>
      <td>Data domain and internal boundaries can be tested.</td>
    </tr>
    <tr>
      <td>
        <strong>Time </strong>
      </td>
      <td>It is less exhaustive and time-consuming.</td>
      <td>Exhaustive and time-consuming method.</td>
    </tr>
    <tr>
      <td>
        <strong>Algorithm test</strong>
      </td>
      <td>Not the best method for algorithm testing.</td>
      <td>Best suited for algorithm testing.</td>
    </tr>
    <tr>
      <td>
        <strong>Code Access</strong>
      </td>
      <td>Code access is not required for Black Box Testing.</td>
      <td>White box testing requires code access. Thereby, the code could be stolen if testing is outsourced.</td>
    </tr>
    <tr>
      <td>
        <strong>Benefit</strong>
      </td>
      <td>Well suited and efficient for large code segments.</td>
      <td>It allows removing the extra lines of code, which can bring in hidden defects.</td>
    </tr>
    <tr>
      <td>
        <strong>Skill level</strong>
      </td>
      <td>Low skilled testers can test the application with no knowledge of the implementation of programming language or operating system.</td>
      <td>Need an expert tester with vast experience to perform white box testing.</td>
    </tr>
    <tr>
      <td>
        <strong>Techniques</strong>
      </td>
      <td>
        <p>Equivalence partitioning is Black box testing technique is used for Blackbox testing.</p>
        <p>Equivalence partitioning divides input values into valid and invalid partitions and selecting corresponding values from each partition of the test data.
         </p>
        <p>Boundary value analysis</p>
        <p>checks boundaries for input values.</p>
      </td>
      <td>
        <p>Statement Coverage, Branch coverage, and Path coverage are White Box testing technique.</p>
        <p>Statement Coverage validates whether every line of the code is executed at least once.</p>
        <p>Branch coverage validates whether each branch is executed at least once</p>
        <p>Path coverage method tests all the paths of the program.</p>
      </td>
    </tr>
    <tr>
      <td>
        <strong>Drawbacks</strong>
      </td>
      <td>Update to automation test script is essential if you to modify application frequently.</td>
      <td>Automated test cases can become useless if the code base is rapidly changing.</td>
    </tr>
  </tbody>
</table>



**[⬆ Back to Index](#index)**
