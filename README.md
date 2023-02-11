# Test-automation-framework-in-web-based-applications
A framework that automates the web browser. The test cases were created using Selenium IDE and were run on the Jenkins Continuous Integration Pipeline. Jenkins was used to reliably build, test and deploy our test cases in one place using CI/CD Pipeline. A test report is also generated at the end of every test we automated using TestNG framework.

TABLE OF CONTENTS

Chapter No.              Topics                                                                                                            

Chapter-0                Summary                                                                         
Chapter-1                Introduction 	                   
1.1                            General Introduction                                                                               
1.2                            Problem Statement                                                                                  
1.3                            Significance/Novelty of the problem                                                     
1.4                            Empirical Study                                                                         
1.5                            Brief Description of the Solution Approach                                              
1.6                            Comparison of existing approaches to the problem framed                      

Chapter-2                Literature Survey	
2.1                            Summary of papers studied                                                                      
2.2                            Integrated summary of the literature studied     
2.3                            Critical Analysis of research paper read

Chapter-3               Requirement Analysis and Solution Approach
3.1                            Overall description of the project                                                        
3.2                            Requirement Analysis                                                                            
3.3                            Solution Approach                                                                                   

Chapter-4                Modeling and Implementation Details
4.1                            Design Diagrams
      4.1.1                       Use Case diagrams                                                                                 
      4.1.2                       Class diagrams / Control Flow Diagrams                                              
      4.1.3                       Sequence Diagram/Activity diagrams                                                   
4.2                            Implementation details                                                                     
4.3                            Risk Analysis and Mitigation                                                              

Chapter-5               Testing (Focus on Quality of Robustness and Testing)
5.1                            Testing Plan                                                                                                           
5.2                            Component decomposition and type of testing required                    
5.3                            List all test cases in prescribed format                                                        
5.4                            Error and Exception Handling                                                              
5.5                            Limitations of the solution                                                                    

Chapter-6                Findings, Conclusion, and Future Work
6.1                             Findings                                                                                            
6.2                             Conclusion                                                                                          
6.3                             Future Work                                                                                         

Chapter-7                References                                                                                           

SUMMARY
Test Automation software is the best way to increase the effectiveness, efficiency and coverage of software testing. Manual testing can’t be repeated and extended, it is impossible to do so. Therefore, we shift to automation tests. Automated tests can be run over and over again at no additional cost and they are much faster than manual tests. Automated software testing can reduce the time to run repetitive tests from days to hours.
We have built a number of  test cases as a few applications of our framework. They show how we can test our code efficiently and with very less manual effort. These test cases are to be  automated and are written in Java in the Selenium Integrated Development Environment developed by Thoughtworks(Thoughtworks India | A global technology consultancy | Thoughtworks). A  test report is also generated at the end of every test we automated using the TestNG framework.A repository for our code is created using GitHub, so that Jenkins can directly catch our code from GitHub which eases the process of automating. Finally, Jenkins was used to reliably build, test and deploy our test cases in one place using CI/CD Pipeline.

1.1   General Introduction
The software development tests its products, yet the delivered software always has defects. But  to catch them before the product is released is important and necessary but they reappear and hamper the best manual testing processes. Test Automation software is the best way to increase the effectiveness, efficiency and coverage of your software testing. Manual testing can’t be repeated and extended, it is impossible to do so. Therefore, we shift to automation tests. Automated tests can be run over and over again at no additional cost and they are much faster than manual tests. Automated software testing can reduce the time to run repetitive tests from days to hours.

1.2   Problem Statement
Test Case Automation framework for Java based applications.

1.3   Significance/Novelty of the problem
Manually repeating these tests is costly and time consuming. Once created, automated tests can be run over and over again at no additional cost and they are much faster than manual tests. Automated software testing can reduce the time to run repetitive tests from days to hours.

1.4   Empirical Study (Field Survey/Existing Tool/Survey/Experimental Study)
The technological developments in big data infrastructure, analytics, and services allow firms to transform themselves into data-driven organizations. Moreover, big data helps companies to achieve higher performance like faster problem-solving issues that used to take years to be solved are now taking less time, hence saving the company various dollars and man-hours.
For example)  If we have ten teams in our company each consisting of ten developers and each developer works on 10 features per day and runs their test scenarios and generates their reports. In that case we will have 100 scenarios per team and 1000 per day for the whole company. These  data are therefore large and the use of big data will allow us to save data processing time.
For companies of all sizes, we  need a strategy for big data and a plan of how to collect, use, and protect it. Every firm needs to build capabilities to leverage big data in order to stay competitive.

1.5   Brief Description of the Solution Approach
Automation of test cases is a highly efficient and a feasible alternative to manual testing and it is achieved with the help of a handful of tools and frameworks namely Selenium, Jenkins, Maven.
All these things play a crucial role in the process of automation. Their role is as discussed: 
-Selenium is the most popularly used freeware and open source automation tool. The benefits of Selenium for Test Automation are immense. Importantly, it enables record and playback for testing web applications and can run multiple scripts across various browsers.
-Maven is a built automation tool from Apache Software Foundation and is commonly used to handle Java projects. Initially, it was developed to simplify the build process of the Jakarta Turbine Project. Nowadays, it is widely used to manage project dependencies and the whole lifecycle of any project.
-Jenkins is a popular CI orchestration tool. It provides numerous plugins for integration with multiple test automation tools and frameworks into the test pipeline. When it comes to Test Automation, Jenkins provides plugins that help run test suites, gather dashboard results, and provide details on failures.

1.6  Comparison of existing approaches to the problem framed
In comparison to its counterparts like HP QTP, IBM RFT, TestComplete which are used for test automation but require a license, are very costly and work only with older versions of Windows; Selenium is open source, free of cost, has community support, supports a variety of operating systems like Windows, Linux & Mac and also supporters various languages like Java, C#, Ruby, Python, Perl & PHP.
![image](https://user-images.githubusercontent.com/124431862/218249748-ef862e1b-2c70-4be1-bdfd-0ef5b7fb42c0.png)

Chapter-2:   Literature Survey

2.1   Summary of papers studied
We have studied some research papers by different authors and the parts that  we have implemented in our project is on the basis of their findings. The literature we studied revolved around some basic ideas that are the backbone of the automation process that we see in the IT industry. We found studies discussing different frameworks and tools used in the automation process for example Selenium, Jenkins, Maven and GitHub. Finally we implemented all of these in our project in order to achieve our final goal that is an Automation Testing Framework for Java based applications.

2.2    Integrated summary of the literature studied
The literature we studied revolved around using different frameworks, its advantages, disadvantages and its  improvements in overcoming the challenges faced in earlier frameworks. Frameworks  also target different test cases and build their specializations as and when required which are frequently used.

2.3  Critical Analysis of research paper read
Research Paper #1 : Niranjanamurthy, Arun Kumar, Sahana Srinivas, Manoj RK
Research Study on Web Application Testing using Selenium Testing Framework. This paper discussed Selenium, Selenium IDE – Most commonly used commands, Need of Selenium, Selenium Test Package, comparison with QTP, advantages and disadvantages of Selenium.
Research Paper #2 : Deepthi Wilson R PG Student Dept. Computer Science & Engineering GSSSIETW Mysore, India and Manjuprasad B Assistant Professor Dept. Computer Science & Engineering GSSSIETW Mysore, India
A Comprehensive Review on Selenium Automation Testing Tool. The objective of this paper is to make test automation intended for Web applications using Softwaretesting tool, Selenium. Research Paper #3 : Milad Hanna , Amal Elsayed Aboutabl , Mostafa-Sami M. Mostafa Automated Software Testing Framework for Web Applications. This study aims to propose a new automated testing framework for testing web applications that enhances the automating process.
Research Paper #4 : Satish Gojare, Rahul Joshi, Dhanashree Gaigaware 
Automated Software Testing Framework for Web Applications. In this paper we have proposed a new automation testing framework to test the web based applications based on selenium webdriver.
Research Paper #5 : Chongwen Wang Professor School of Software, Beijing Institute of Technology, Beijing, China
The Research and Design of NSL-Oriented Automation Testing Framework. By analyzing the Selenium and other open source testing tools, the lack of Selenium and the design of testing scripts are given to discuss and try to improve to resolve problems of NLS. 
Research Paper #6 : Calysta Merina Department of Informatics Syarif Hidayatullah State Islamic University Jakarta, Indonesia Nenny Anggraini Department of Informatics Syarif Hidayatullah State Islamic University Jakarta, Indonesia Sandra H. Afrizal Department of Public Health Science Universitas Indonesia Depok, Indonesia Nashrul Hakiem Department of Informatics Syarif Hidayatullah State Islamic University Jakarta, Indonesia
A Comparative Analysis of Test Automation Frameworks Performance for Functional Testing in Android-Based Applications using the Distance to the Ideal Alternative Method. The results show that Calabash has the best performance among the other frameworks with a 0 value for the DIA Method that indicates that Calabash has zero distance to the ideal alternative.

Chapter-3:  Requirement Analysis and Solution Approach
3.1  Overall description of the project 
Our project is basically a framework that automates the web browser. We used the Selenium IDE for creating our test cases and the Maven tool was used to provide all the dependencies for the test cases to build and run. We also pushed our code to the GitHub repository so that the Source Code Management becomes feasible. Finally, we ran our test cases on the Jenkins Continuous Integration Pipeline.

3.2   Requirement Analysis (Functional/Non-Functional/Logical Database requirements)
The database that was required was a functional database of web applications which was the backbone of our automation.

3.3   Solution Approach (algorithms or hardware used)
There was no algorithm or hardware used in this project.

Chapter-4:   Modeling and Implementation Details
4.1   Design Diagrams
      4.1.1  Use Case diagrams
      ![image](https://user-images.githubusercontent.com/124431862/218250200-e5790ec2-7c12-446e-a380-c1f4c49911fc.png)
      4.1.2  Class diagrams / Control Flow Diagrams
      ![image](https://user-images.githubusercontent.com/124431862/218250214-67fd9ca5-ffd5-4980-9f9c-1d4ec6eec45d.png)
      4.1.3  Sequence Diagram/Activity diagrams
      ![image](https://user-images.githubusercontent.com/124431862/218250220-d121da18-7812-4a32-9dde-e1707e4fd6a7.png)
      ![image](https://user-images.githubusercontent.com/124431862/218250223-79d6f939-ff91-4a3e-97fd-0b6bfa7b2250.png)

4.2   Implementation details 
Our test cases that are to be automated were written in Java in the Selenium Integrated Development Environment developed by Thoughtworks(Thoughtworks India | A global technology consultancy | Thoughtworks). 
We generated an after test report of every test we automated using the TestNG framework.
Then, we used Maven which is a project comprehension tool. It  was required to provide our project with all the prerequisites and dependencies. It was also used to build our test cases using the maven command line called in our Jenkinsfile.
We created a repository for our code using GitHub, so that Jenkins can directly catch our code from GitHub which eases the process of automating.
Finally, Jenkins was used to reliably build, test and deploy our test cases in one place using CI/CD Pipeline.

4.3   Risk Analysis and Mitigation
●	There is a huge amount of investment made to get automation going in any project. However, the cost of setting up automation and making it work is high. The return is slow and takes time.
●	With constantly evolving technology it is seen that testers and testing need to be innovative in terms of testing solutions, architectures, strategies and tools. This is an obvious risk as it tends to slow down the progress of the project. The testers and testing need to constantly evolve alongside.
●	Test automation is heavy on maintenance. And that’s why it is important to understand and cover for the investments.
●	Technology is not only evolving but also getting more and more complex, which means that the learning curve for testers is getting steeper by the day. There is a need for testers to keep abreast with modern technology not just for developers but also for testers. 
●	With the pressing need for testing and growing demand to constantly deliver better products. There is a need to choose effective strategies to carry out. Also, the automation strategies would have to be targeted to help test across the right layer and meet the demands of end to end test automation.

Chapter-5:   Testing
5.1  Testing Plan
A test automation strategy defines the process of execution and management of test cases. Text execution outlines things like day-to-day tasks and procedures related to automation. We have considered the following when executing test cases:
●	We have added automated test cases to the regression suite, ran and verified multiple times to ensure they run as expected.
●	We have defined a set of best practices that make test cases resistant to changes in the system which is being automated.
●	We have used a pipeline orchestrator (Jenkins) to execute test cases.
●	It assigns status ‘Pass’ or ‘Fail’ to the test case after execution,  this status is assigned to the test cases automatically as per defined success criteria.
●	If the status is ‘Fail’, perform failure analysis.

5.2  Component decomposition and type of testing required
Every test case was divided into 3 components namely: 
●	@BeforeClass : It marks the startup phase of the test case in which all the prerequisites are completed such as setting up the WebDriver (Chrome WebDriver in our case). 
●	@Test: In this component the actual testing takes place in which the WebDriver fetches all the details from the web browser.
●	@AfterClass: This is the ending component of every test case in which the success condition was checked and the WebDriver was closed marking the end of a test case.
After the test cases are created, they are pushed to the GitHub repository and then integrated with Jenkins.
![image](https://user-images.githubusercontent.com/124431862/218250128-2b311939-a3f4-4b2b-82e1-c84787143c34.png)
![image](https://user-images.githubusercontent.com/124431862/218250153-dd91ab1b-85ca-417f-b861-454072046202.png)
 
5.3    List all test cases in prescribed format
a)	Finding iPhone on Amazon in the range 40000 to 60000
![image](https://user-images.githubusercontent.com/124431862/218249907-6bd3e35a-5b88-4f20-847b-5cde328d96f3.png)
![image](https://user-images.githubusercontent.com/124431862/218249913-c1918d1b-fac9-4bb2-b3b3-97790d2f83cd.png)

b)	Searching “What is the weather today” on google
![image](https://user-images.githubusercontent.com/124431862/218249928-7d21dd26-8936-49cb-ad76-e01a42f294dd.png)
![image](https://user-images.githubusercontent.com/124431862/218249936-08a1df0a-a7cc-4fb7-9e6c-03da862e84ad.png)

c)	“Searching google doodles” on google
![image](https://user-images.githubusercontent.com/124431862/218249941-106eff84-98bb-4630-92b8-64a11f183c21.png)
![image](https://user-images.githubusercontent.com/124431862/218249944-15bc6bf1-66bd-4fdb-a775-205174ee7410.png)

d)	Searching Hindi Movies on Disney Plus Hotstar
![image](https://user-images.githubusercontent.com/124431862/218249950-d7a6f122-2b77-4ec7-b28c-f72d6d657a78.png)
![image](https://user-images.githubusercontent.com/124431862/218249952-949a110a-3edc-4328-b0e5-f3c59cc11544.png)

e)	Searching a course for Data Structures And Algorithms on Geeks For Geeks
![image](https://user-images.githubusercontent.com/124431862/218249963-69cdcc00-8100-41c6-8874-1eea4f630fa2.png)
![image](https://user-images.githubusercontent.com/124431862/218249974-2552f5fe-a87d-47e6-86c1-1f5f8bff99ab.png)

f)	Finding Solution to an error on StackOverflow
![image](https://user-images.githubusercontent.com/124431862/218249986-b649bdf3-5f29-4e99-b06f-c01a35951fa4.png)
![image](https://user-images.githubusercontent.com/124431862/218249990-aefa92fd-74f9-4b2b-a762-3e10d9a28625.png)

g)	Downloading a game from website
![image](https://user-images.githubusercontent.com/124431862/218249996-9d29739e-03a6-4910-8ec7-e32b226e0f47.png)
![image](https://user-images.githubusercontent.com/124431862/218250002-812a4bf8-1f45-4cca-9f6f-96d33cf5c37b.png)

5.4     Error and Exception Handling
We experienced an error where our WebDriver was unable to find the needed web element using the XPath method. The error was “unable to find the specified element with xpath(The XPath of that element)”. We realized that the loading time of the webpages was creating the problem in which our code was requesting for the element which was not yet loaded. So, for handling this we implemented a function: manage().timeouts().implicitlyWait(30, TimeUnit.SECONDS)
which delayed the driver which was finding the specified web element so that the page could load first.

5.5    Limitations of the solution
●	One of the limitations that we have come across which causes the failure of our test case is basically a random intrusion of a pop-up which becomes a hurdle to figure out the element using the XPath that we have given. We still have to figure out how we can handle or ignore such pop-ups.
●	Also the XPath method of finding a web element to work on is not reliable. For accuracy,  a strategy needs to be created which  must have knowledge about the webpage we are visiting every time in order to accurately determine which method to use to uniquely identify a web element.

Chapter-6:  Findings, Conclusion, and Future Work
6.1   Findings
The quality of the product is the number one priority, it is strongly advocated using automated testing as part of our regular day-to-day development practices. It  ensures  that the  application is tested properly and gives confidence to developers, management and customers alike.
Automated testing has an upfront cost and they do take the time to develop. The investment pays off in the long term, in terms of reduced workload, eliminating manual errors, accuracy, and savings on cost and time.
Overall, automated testing is a faster way to get feedback on failures than manual testing, in line with the principles of “Fail fast, Fail early”. It helps to ensure quality in a way manual testing never will be able to.

6.2   Conclusion
At the end of the project we learned how to automate web applications using all the frameworks and tools mentioned above. We realized that test automation is a very crucial part of software development as the reliability and longevity depends on it. Using the Jenkins server we were able to build and test our code very efficiently and with very less manual effort.  Other tools also had a big impact in the automation process for example the TestNG framework was used to acquire an after test report which enabled us to rectify an anomaly in our code. On the other hand the Maven repository helped us provide all the prerequisites for our test cases making sure the automation process does not lack anything. Finally, we were able to achieve a very efficient test case automation framework. 

6.3    Future Work
●	After the automation process is done, the final build that has gone through many test cases would finally be deployed using the Jenkins Continuous Deployment Pipeline and the final build is released for production.
●	We could also overcome the limitations occurring in the existing test cases that a random popup might cause failure.
●	There are immense applications that can be used not just for text but also for image based tests, AI bots for automation, etc.

References   
[1]	“Before you continue to YouTube.” [Online]. Available: https://www.youtube.com/@RaghavPal. [Accessed: 26-Sept-2022].
[2]	“Stack Overflow - where developers learn, share, & build careers,” Stack Overflow. [Online]. Available: https://stackoverflow.com/. [Accessed: 9-Oct-2022].
[3]	B. Deb, “Risks in test automation - going beyond the obvious,” TestProject, 30-Nov-2020. [Online]. Available: https://blog.testproject.io/2020/11/30/risks-in-test-automation-going-beyond-the-obvious/. [Accessed: 21-Nov-2022].
[4]	“Software engineering,” GeeksforGeeks, 01-May-2019. [Online]. Available: https://www.geeksforgeeks.org/software-engineering-automated-testing/. [Accessed: 11-Nov-2022].
[5]	“Java tutorial,” W3schools.com. [Online]. Available: https://www.w3schools.com/java/default.asp. [Accessed: 12--Nov-2022].
[6]	“How to launch Jenkins Selenium tests using the pipeline,” Digital.ai, 23-Nov-2022. [Online]. Available: https://digital.ai/catalyst-blog/how-to-launch-jenkins-selenium-tests-using-the-pipeline/. [Accessed: 20-Oct-2022].




