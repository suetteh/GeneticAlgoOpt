## Optimize University Part-time Programs Scheduling Using Genetic Algorithm

This study attempted to use computational intelligence algorithm to solve a real-world optimisation problem. Specifically, genetic algorithm (GA) was utilized to generate course schedule for three part-time modular programmes offered by the Asia Pacific University. The part-time structure comprises 5 intakes a year and students are required to take only one module in each intake. 
In order to adapt to the requirements given, 7 hard constraints and a soft constraint were applied to the SE and AI programs while 8 hard constraints and a soft constraint for the DSBA program. 

Two experiemnts were conducted to compare the performance of the combination of tournament selection and single point crossover, as well as Stochastic Universal Sampling selection and two point crossover.

### Challenges:
Multiple hard constraints are required to be solved. Primarily, the schedule should ensure that each existing and new student has a module to take in each intake so that they are able to complete the programme within 2.5 years. However, a module should not run in consecutive intakes. Concurrently, the operational costs to the university should be minimize. Hence, only a maximum of 5 modules to be offered per intake for each programme. A further complication is that certain modules are offered in two or three programmes which means that these shared modules should be offered at the same intake. Lastly, the research methods module must be offered 3 times a year in January, May and October.

### Library:
Distributed Evolutionary Algorithms (DEAP)

numpy

pandas

itertools

matplotlib 

### Conclusion:
Genetic ALgorithm is a helpful tool in scheduling. With generation=100, single point crossover, tournament selection acheived better results. The final schedule is as shown the [Result](https://github.com/suetteh/GeneticAlgoOpt/blob/main/Results.pdf) file.

### Possible Improvement:
In this study, GA was able to keep all hard constraint violations at 0. However, the cost spent by the university might be able to further minimize by maintaining each module to be run not more than twice. Grid search or random search can be applied for hyperparameter tuning. Besides that, other algorithm such as Particle Swarm Optimization (PSO) may further improve the outcome. 

Data:
The StuRec files consists of the list of existing students of the respective programs with the list of modules taken.
The PT Timetable files include the core modules and electives of the respective programs.

