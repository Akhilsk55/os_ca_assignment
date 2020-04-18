# os_ca_assignment
#Name - Akhil p
#Roll no - 46
#Reg no - 11807586
Q15)
solution -- \
Implementation (Algorithm):\
1- Traverse until all process gets completely\
   executed.\
   a) Find process with minimum remaining time at\
     every single time lap.\
   b) Reduce its time by 1.\
   c) Check if its remaining time becomes 0 \
   d) Increment the counter of process completion.\
   e) Completion time of current process = \
     current_time +1;\
   e) Calculate waiting time for each completed \
     process.\
   wt[i]= Completion time - arrival_time-burst_time\
   f)Increment time lap by one.\
2- Find turnaround time (waiting_time+burst_time).\
Example \
 PROCESS	DURATION	ORDER	ARRIVAL TIME\
P1	9	1	0\
P2	2	2	2\
Answer\
P1 waiting time: 4-2 = 2\
P2 waiting time: 0\
The average waiting time(AWT): (0 + 2) / 2 = 1\
Solution code - SJF_scheduling.c
