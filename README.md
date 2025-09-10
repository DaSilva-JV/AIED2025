# Resource allocation to unknown tasks
Dynamic Allocation of Human Resources for Multi-attempt Tasks

Abstract: In this paper, we study a generalization of the task allocation
problem and propose an algorithm to solve it. In this problem, a finite
number of human resources are available sequentially to try to fulfill a
set of tasks. Each interaction results in only two possible outcomes: the
task is correctly fulfilled or the resource fails. Each human resource is
available to try an independent number of tasks and each task must be
fulfilled a predetermined number of times. Item Response Theory (IRT)
is used to model resources, tasks, and the probability of success. The
IRT parameters of resources and tasks are unknown. Bayesian inference
is used to assess these parameters as more information becomes avail-
able through the interaction between resources and tasks. Our algorithm
combines shadow test replanning to plan under uncertain knowledge and
optimally allocating tasks to resources; aiming to maximize the number
of solutions. We also performed simulations to maximize the minimum
number of solutions a task received. In our simulations, we define five
scenarios for the availability of the resources and the number of solutions
each task must receive. The results were compared with two baselines:
random allocation and the heuristic easier-first. Real-world data was
used from the Brazilian Baccalaureate Examination (ENEM).
