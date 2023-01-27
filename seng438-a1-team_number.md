>   **SENG 438 - Software Testing, Reliability, and Quality**

**Lab. Report \#1 – Introduction to Testing and Defect Tracking**

| Group: Group Number 10
|-----------------|
| Student 1: Rachel Dalton  
| Student 2: Ana Clara Perrone   
| Student 3: Saina Ghasemian-Roudsari
| Student 4: Isaiah Lemieux   


**Table of Contents**

(When you finish writing, update the following list using right click, then
“Update Field”)

[1 Introduction	1](#_Toc439194677)

[2 High-level description of the exploratory testing plan	1](#_Toc439194678)

[3 Comparison of exploratory and manual functional testing	1](#_Toc439194679)

[4 Notes and discussion of the peer reviews of defect reports	1](#_Toc439194680)

[5 How the pair testing was managed and team work/effort was
divided	1](#_Toc439194681)

[6 Difficulties encountered, challenges overcome, and lessons
learned	1](#_Toc439194682)

[7 Comments/feedback on the lab and lab document itself	1](#_Toc439194683)

# Introduction
In this lab our group was introduced to several different concepts and practices that we covered in lectures. This lab gave us the opportunity to apply these concepts in an interactive and hands-on experience. Before starting this lab, we knew that that exploratory and manual functional testing were two branches of differents kinds of testing activities. Exploratory testing is human-based, and tests are designed and executed concurrently. Design test values are based on the combination of domain knowledge of the program and human knowledge of testing, to create "realistic" scenarios that will cause software either to fail or to fulfill its mission. This is exactly the approach we took during this phase of the lab, initially creating a plan before starting to test. Since we performed this step in partners, we each created our own plans, however, in the end both pairs took a very similar approach in order to follow the principles of exploratory testing. Starting with reading the requirements of the ATM simulation system and understanding its functionality, this allowed us to come up with tests that we thought would both pass and fail. Making sure to test varying inputs (legal versus illegal values for example), this allowed us to observe whether or not the system was functioning according to its specifications. Exploratory testing is "about enabling choice not constraining it" and we certainly felt as though this step of the lab gave us a lot of freedom to, sure enough: explore. Manual scripted testing then follows a path that is written by either the tester themselves, or in our case someone else. This approach follows a script that includes test cases and test steps that are documented, both of which do not deviate from the path laid out in this script. Manual Regression Testing can be done after this in order to check that a system update does not reintroduce faults that have been corrected earlier. And so we performed both of these practices, firstly following the script we were given and after this executing the same tests with an updated version of the ATM simulation system. Issue tracking was very important during each one of the different testing approaches. This lab not only gave us the opportunity to put these testing methods to practice but it equally allowed us to learn more about issue tracking systems and the significance of writing effective bug reports.

# High-level description of the exploratory testing plan
Testing pair 1: Saina and Rachel

Exploratory testing plan:
Our plan is to first read and understand the requirments for the ATM simulation system as outlined in Appendix B. We plan to approach the ATM simulator in functions we want to target. Within those functions tesing each of the test with the most common paths, and exceptional paths we can think of to ensure the ATM is able to make the correct type of transactions based on what the user requests. We will also test incorrect inputs to ensure the ATM does not process with incorrect inputs. Then recording any incorrect outputs based on the input requirments in our bug report software (Jira).                                                                                                    

Functions being targeted:
1. We want to ensure each of the buttons in the simulator work. The buttons to test are to turn system on, off, enter, clear, cancel and show log. These buttons will be pressed at random times to ensure they can always correctly work.
2. Testing incorrect card inputs/correct card inputs.
3. Testing both Card 1 and Card 2
4. Testing incorrect pins for correct cards.
5. Testing all four transaction types with both cards: withdrawal, deposit, transfer, and balance inquiry. Within each of the transaction types ensuring the correct amount of money is taken out, put in, transfered, and displayed based on the amounts we select.

Testing pair 2: Isaiah and Ana

Exploratory testing plan:
1. Read high-level requirements for ATM service in Appendix B of the lab handout. Our plan is to create a limited amount of test cases for all functionalities of the ATM.
2. For each requirement, run a series of tests that ensure the coverage of a common input, an edge-case input, an input that should pass, and an input that should fail. Record the result next to the test. While the tests are being run, display the document containing the list of the functional requirements next to the ATM machine to ensure no functionalities are neglected. Highlight requirements as they are tested.
3. For each test that fails, create in issue and description on Jira.
 
# Comparison of exploratory and manual functional testing
rachel, saina
Text…

-   Note that you need to submit a report generated by your defect tracking
    system, containing all defects recorded in the system.

# Notes and discussion of the peer reviews of defect reports
group
Text…

# How the pair testing was managed and team work/effort was divided 
After reading the lab handout and confirming that everyone had a general understanding of how the program works, expected testing process, and program functionality, we split the group into two pairs. Saina and Rachel, Isaiah and Ana. At this point, we planned to carry out exploratory testing completely separate, without talking about our testing process to avoid risk of a pair being influenced to avoid testing something if the other pair had already done it. In order to do this, we also had to hide all issues entered by members of the other pair so we could start out with a clean slate. Each group would also create a pre-testing plan to use as a guide through the exploratory testing phase on version 1.0 of the ATM program. The plan specified would describe the domain of testing (how much functionality would be tested, and to what depth), and how each test would be carried out.

# Difficulties encountered, challenges overcome, and lessons learned
To start both pairs that were doing exploratory testing were a bit overwelmed. This was due to the ATM simulation being new to us causing a bit of a slow start on the first couple tests, but the challenge was overcome as the more we used the system it became very quick to navigate through by the time we got to regression testing stage. Another difficulty encountered was documenting bugs using the issue tracking system Jira as this was a system that was new to all memebers of the group. The last diffculty which was very time consuming was that both pairs spent a bit too much time doing exploratory testing and attempting to test every common path/excetional path that could cause bugs. One of most important lesson learned was in regards to using the Jira. Our group learned that when reporting issues it would have been beneficial to note which version of the simulator we were using. Another extremly important lesson learned was that we should write which steps we are taking when going through exploratory scripted testing such as writing down which card was being used, which type of transaction was made, and how much money we had originally put in. As at the start we did not write down each of the steps we were using and we quickly realized that was making it much more difficult to add details in the bug reports. As for example Card 1 and Card 2 would have some bugs that were different and same with doing different transactions in each of these cards and not keeping track of which card we were in for example would cause us to have difficulty determining the specifics of bugs. This showed our group that you are not able to make any assumptions when testing as we assumed the cards both had the same bugs which is why we did not keep track of the steps at first.

# Comments/feedback on the lab and lab document itself
Our group found this lab a very useful practice for learning how to a use issue tracking system and learning the importance of writing effective bug reports. As well as how having detailed bug reports helps you when you are resolving bugs. In terms of feedback on the lab, although we managed to finish things on time, we did find we were in a bit of a time crunch with only one week to do it. The lab document was very detailed and straightforward, however, at some points we found ourselves scanning through it multime times to find the information we needed. Perhaps if it included a numbered list of the steps of the lab after the introductory material, it would be somewhat easier to understand the order of the different deliverables.


