# Improved_CPU_Scheduling_Algorithm
<h5>
In computing, scheduling is the method by which work specified by some
means is assigned to resources that complete the work. The work may be
virtual computation elements such as threads, processes or data flows, which
are in turn scheduled onto hardware resources such as processors, network
links or expansion cards.
  
A scheduler may aim at one or more of many goals, for example: maximizing
throughput (the total amount of work completed per time unit); minimizing
wait time (time from work becoming enabled until the first point it begins
execution on resources); minimizing latency or response time (time from work
becoming enabled until it is finished in case of batch activity, or until the
system responds and hands the first output to the user in case of interactive
activity);or maximizing fairness (equal CPU time to each process, or more
generally appropriate times according to the priority and workload of each
process). In practice, these goals often conflict (e.g. throughput versus
latency), thus a scheduler will implement a suitable compromise.

A process is an instance of a program running in a computer. It includes the
current values of the program counters, all the registers, and also the
variables. The processes waiting to be assigned to a processor are put in a
queue called ready queue. Burst time is amount of time for which a process is
being held by the CPU. When a process arrives at the ready queue it is the
arrival time. From the time a process is submitted to the time it is completed is
the turnaround time. When a process waits in the ready queue that time is the
waiting time. The number of times CPU gets switched from a process to
another one is called context switching. The optimal and the best scheduling
algorithm will have less waiting time, less turnaround time and less number of
context switches.
</h5>

#Explanation
<h5>The proposed algorithm is called Improved Mean Round Robin with
Shortest Job First (IMRRSJF) algorithm. The basic idea and difference
between this improved algorithm and existing algorithms is that it first
arranges the processes in the ascending order of their CPU burst time.
Also this algorithm calculates the time quantum which is equal to the
square root of mean and CPU burst time. Then the jobs are assigned CPU
according to the shortest job first manner and in the round robin
manner. That is, if a process has a longer burst time than time quantum
it is context switched and assigned CPU later.</h5>
