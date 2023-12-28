# Computational Intelligence Optimization
Optimize University Part-time Programs Scheduling Using Genetic Algorithm

This study attempted to use Genetic Algorithms to generate schedule for three university programs namely the MSc in Data Science and Business Analytics (DSBA), Artitifical Intelligence (AI) and Software Engineering (SE). The schedule generated should cover modules offered for five intakes. 
In order to adapt to the requirements given, 7 hard constraints and a soft constraint were applied to the SE and AI programs while 8 hard constraints and a soft constraint for the DSBA program. 

Hard constraints:

i) Avoid same module offered in consecutive intakes and within same intake

ii) All modules is offered at least once

iii) The number of modules offered should be less than five

iv) Every new and existing student must have a module to take in every intake.

v) The modules offered in each intake should be different.

vi) The schedule must have 5 intakes.

vii) Student should not take more elective modules than required for their respective program. 

viii) Student should only take the respective modules for either Business Intelligence (BI) or Data Engineering (DE) pathway.

Soft Constraint:

i) Each module should not be offered more than twice throughout the five intakes.

Two experiemnts were conducted to compare the performance of the combination of tournament selection and single point crossover, as well as Stochastic Universal Sampling selection and two point crossover.

Data:
The StuRec files consists of the list of existing students of the respective programs with the list of modules taken.
The PT Timetable files include the core modules and electives of the respective programs.

Conclusion:
Genetic ALgorithm is a helpful tool in scheduling. With generation=100, single point crossover, tournament selection acheived better results. The final schedule is as shown the 'Result'(https://github.com/suetteh/GeneticAlgoOpt/blob/main/Results.pdf) file.
