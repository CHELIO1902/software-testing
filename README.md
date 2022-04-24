# Software Testing Fundamentals

Here you will find fundamentals of modern testing, testing from tester's and developer's
perspective, tips, techniques, strategies to do software testing, and so on.

This will definitely improve your software's quality.

## Index
-   [Intro](#intro)
-   [Black Box Testing](#black-box)
-   [White Box Testing](#white-box)


### --- Intro ---

The main reason why many users quit from using a certain software, it's because its
performance is slow, buggy, does not work on certain devices, and so on.

Testing software is just as important as developing it. In order to deliever a great UX,
make sure everything works, scale, we need to test our software.

But first, let's talk about Black Box Testing and White Box Testing.

**[⬆ Back to Index](#index)**


### --- Black Box Testing ---

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

**[⬆ Back to Index](#index)**


### --- White Box Testing ---



**[⬆ Back to Index](#index)**
