# Airline_Crew_Scheduling
The goal is to understand the problem faced by aviation industry while deciding optimal schedules for its operation and try to generate feasible solutions for it.
## Abstract

The project is addressing the problem faced by the aviation industry while scheduling its operations. The crew scheduling problem is often divided into crew pairing and crew assignment due to the large size of the problem and the complexity of constraints formed due to safety standards enforced by regulating authorities and labor unions. There are two types of formulations commonly used for these problems, known as a set covering problems and set partitioning problems. We have explored the set covering and set partitioning formulation in this project and tried to solve the problem using the column generation approach and multi-label shortest path algorithm to generate suitable schedules which 
satisfy all constraints.

## Problem Statement
The airline crew scheduling problem is often divided into crew pairing problem and crew assignment problem due to the large size of the problem and very high complexity. Crew pairing problems are associated with finding a set of minimum-cost pairings such that each scheduled flight over the time horizon is included in precisely one pairing.Crew assignment combines the generated pairings with vacations, training schedules and other breaks for the crew members. We have found out good crew pairings satisfying all constraints and having minimum cost over a timeline considering ten flights. We generated the crew schedules for individual crew member based on their vacation preferences, prescheduled training and satisfying all rules imposed by regulatory authorities. There are two types of schedules possible in crew assignment : 
1) Bidline schedules 2) Personalized schedules

## Solution Approach
The problem is modelled using set partitioning formulations and To solve the set partitioning problem, we used a column generation approach with a multi-label shortest path algorithm to find valid crew pairings. We have generated a schedule based on bid line schedules and studied an extended formulation of the set covering problem from Kasirzadeh et al. (2017).

## Key takeaways From this project :
I have :

• Reviewed the Column Generation method for solving  the Large Scale Integer programming problems

• Modelled the personalized crew assignment problem using set partitioning and set covering formulation

• Generated the schedule of 7 flights using 10 suitable pairings spanning across 4 destination airports

• Implemented Multilabel Shortest Path Algorithm to obtain feasible solutions from coloumn generation

### To know more details 
Read asirzadeh et al. (2017). and our report <href src="https://github.com/sandesh-30/Airline_Crew_Scheduling/blob/main/Air_line_Scheduling.pdf">
