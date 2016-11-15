# Full_System_Simulators

Using GEM5 as a tool. 
We want to do comparison between Full System Simulation and Processor Simulator.

M5 or gem5 full simulator:

	-> Full simulator which also simulates the OS(possibly unix)
	-> Execute same program on this M5 and simplescalar and plot various matrix
	-> like l1 cache misses, l2 cache misses, simulation time, branch prediction
	-> Compare both the results

Objective 1: The objective here should be to be able to recommend for what type of programs Full simulation is helpful and for what processor 		     simulation is helpful

Objective 2: Is there any difference between the matrix for same program, why are they different, which simulation is better

Objective 3: Is processor simulation always recommended ?

Objective 4: Can we modify Simplescalar to handle some library calls(which might be executing frequentlly) which will improve simulation ?

Constraints : 1. Set same architecture in both simulators
	      2. Set same cache and other reg size
	      3. If possible instruction set should be same 
