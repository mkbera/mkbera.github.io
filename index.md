## About me

I am a senior year undergraduate in the Department of Computer Science and Engineering at IIT Kanpur. I am interested in Machine Learning and Formal Methods. I am also interested in prediction technology involved in computer architecture (e.g., cache replacement policy). 

TODO:
1. upload CV
2. upload poject reports

# Projects

### Sat Based Motion Planning of Multi-Robot System
[report](mkbera.github.io/report.pdf)
1. The aim was to design a tool to find the trajectory of a  multi-robot system under minimum make-span.
2. The main idea was to reduce the problem of motion planning into a SAT problem.  A SAT-solver is used to solve the SAT instance. The output of the SAT solver is then processed to get meaningful information, in our case, the path of the robots.
3. Various optimization techniques were applied to make clause generation faster.
4. The tool was implemented in C++ using the code-base of MiniSAT(a minimalistic, open-source SAT solver).
5. MAX-SAT was also used to minimize sum-of-cost, once the minimum make-span is achieved.
