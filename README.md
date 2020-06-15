Evaluating the impact of DQ_THRESHOLD parameter in PIE algorithm

Brief: Proportional Integral controller Enhanced (PIE) is a popular AQM algorithm deployed in
DOCSIS 3.0 modems of CableLabs, USA. In this project, the main idea is to evaluate the
impact of setting DQ_THRESHOLD on the performance of PIE algorithm.

Required experience: C, C++ and PIE
Bonus experience: Knowledge of Flent.
Difficulty: Low to Moderate

Recommended Reading:
● RFC 8033 (Link: https://tools.ietf.org/html/rfc8033)
● PIE: A Lightweight Control Scheme to Address the Bufferbloat Problem 
● About Flent (Path: https://flent.org/)

Result:
The graphs that we received in Flent for different values of dq_thresh are available in the Graphs folder. We can find that value around 12000bytes gives better bandwidth and lower latency compared to the default value of 16384bytes. 

Team Members:

Vasudev B M (171CO150)
S Sai Girish (16CO244)
Anil Kumar (171CO219)
