## About me

I am a senior year undergraduate in the Department of Computer Science and Engineering at IIT Kanpur. I am interested in Machine Learning and Formal Methods. I am also interested in prediction technology involved in computer architecture (e.g., cache replacement policy). 

TODO:
1. upload CV
2. upload poject reports

# Projects

### Sat Based Motion Planning of Multi-Robot System
[report](mkbera.github.io/report.pdf)
1. Designed a tool to find the trajectory of a  multi-robot system under minimum make-span.
2. Reduced the problem of motion planning into a SAT problem. Used a SAT-solver to solve the SAT instance. Processed the output of the SAT solver is then processed to get meaningful information, in our case, the path of the robots.
3. Applied various optimization techniques to make clause generation faster.
4. Implemented the tool in C++ using the code-base of MiniSAT(a minimalistic, open-source SAT solver).
5. Used MAX-SAT to minimize sum-of-cost, once the minimum make-span is achieved.
