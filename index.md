# Manish Kumar Bera

## About me

I am a senior year undergraduate in the Department of Computer Science and Engineering at IIT Kanpur. I am interested in Machine Learning and Formal Methods. I am also interested in prediction technology involved in computer architecture (e.g., cache replacement policy). 

You can find my resume [here](mkbera_resume.pdf)


# Projects

### Extreme Multi-label Learning via One-Class Classification | Prof. Piyush Rai (IIT Kanpur) | [Ongoing]
1. Explored the use of one-class classifiers in solving multi-label classifications problems, both in binary relevance as well as multi-task setting.
2. Proposed a clustered multi-task one-class method for multi-label problems.
3. Proposed an alternating optimization scheme to speed up the multi-task approach.


### Trust Region Policy Optimization of POMDPs | Prof. Anima Anandkumar (Caltech) | Summer 2018
[report](./reports/surf-trpo.pdf) 
1. Worked on Generalized Trust Region Policy Optimization Techniques for partially observable environments.
2. Explored variants of Proximal Policy Optimization Algorithms for POMDP setting (Partially Observable Markov Decision Process).
3. Looked into limitations of \textit{roboschool} physics engine. Suggested modifications for increasing the convergent episode length of an agent.


### On sharing aware cache replacement policies | Prof. Mainak Chaudhuri (IIT Kanpur) | Fall 2018

[report](./reports/cs622.pdf) | [code](https://github.com/mkbera/multilevel-cache-sim)
1. Worked on improving sharing-aware cache replacement policy for multi-threaded applications.
2. Integrated parsecmgmt(tool for managing PARSEC programs and kernels) with PIN to generate address trace.
3. Implemented three level cache architecture to simulate cache replacement policy.
4. Proposed modifications to existing evaluation metric of prediction strategy.
5. Presented a novel modification to existing prediction policy.



### Sat Based Motion Planning of Multi-Robot System
[report](./reports/report.pdf) 
1. Designed a tool to find the trajectory of a  multi-robot system under minimum make-span.
2. Reduced the problem of motion planning into a SAT problem. Used a SAT-solver to solve the SAT instance. Processed the output of the SAT solver is then processed to get meaningful information, in our case, the path of the robots.
3. Applied various optimization techniques to make clause generation faster.
4. Implemented the tool in C++ using the code-base of MiniSAT(a minimalistic, open-source SAT solver).
5. Used MAX-SAT to minimize sum-of-cost, once the minimum make-span is achieved.

## Other projects

### Detecting Semantically Similar Questions | Prof. Harish Karnick (IIT Kanpur) | Spring 2018
[report](./reports/NLP_Report.pdf) 
1. Formulated methods to detect whether two questions seek same answer.
2. Reviewed and implemented multiple architectures in Tensorflow from scratch.
3. Converted the questions to their vector representation and used Siamese Network to construct similarity space.

### Smart Surveillance | Prof. Medha Atre (Oxford University) | Spring 2018
[report](./reports/smart-surv.pdf) 
1. Came up with automated methods of surveillance.
2. Used recent developments in NLP to learn a definition of anomaly independent of the setting.
3. Proposed a context agnostic methodology to detect anomaly.
4. Integrated our model with Tensorflow Object Detection API.

## Some helpful tools/scripts
1. [utilities](https://github.com/mkbera/utilities): A lock free implementation for parallel programming.
2. [svm-vis](https://github.com/mkbera/svm-vis): A qudratic programming based tool for SVM visualisation.

# Contact
Email: `bera.manish.kumar@gmail.com`  
github: [mkbera](https://github.com/mkbera)
