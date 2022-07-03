#Preference-based Policy Optimization for Multi-Objective Reinforcement Learning

##Abstract
***
We propose a new algorithm for preference based multi-objective reinforcement learning(PBMORL), aiming at using the preference information from 
    the decisionmaker to guide the MORL algorithm to find the optimal policies that really catch the demand of people. In MORL, the target of algorithm is 
    to find a convergent and diverse Pareto-optimal set of policies. However, in general, there are only one part of these policies really achieve the performance that the decisionmaker really needs. PBMORL is proposed to solve the problem of finding such a preference based policy set.  There have been several works on preference  based multi-armed bandits or MORL with discrete environment, however, for continuous environment, the research is far from enough. In this paper, we introduce an interactive PBMORL algorithm for learning preference based Pareto-optimal set of MORL problems with continuous state space and action space. By learning the demand of the decisionmaker during the process of policy optimization, we guide the MORL algorithm to achieve the performance that the decisionmaker really desires.   Experiments both on benchmark test problems and a practical industrial prolem demonstrate the effectiveness of our algorithm.

##Algorithm
***
