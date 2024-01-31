# Lottery-Scheduler

 Implemented a Lottery Scheduler in the xv6 kernel, replacing the default round-robin scheduler.
• Designed and implemented the settickets(int) system call to manage process ticket allocation.
• Developed the getpinfo(struct pstat*) system call for retrieving process statistics in the kernel.
• Ensured proper inheritance of tickets from parent to child processes, maintaining proportional distribution.
• Integrated a pseudo-random number generator into the kernel to support the lottery scheduler.
• Implemented a structured process statistics system, including process ID, number of tickets, and accumulated ticks.
• Created a graphical representation illustrating the lottery scheduler's allocation of time slices.
• Conducted comprehensive testing using sample programs and test cases to validate scheduler functionality.


# Modified xv6 zip file has been provided.

![image](https://github.com/Asim4513/Lottery-Scheduler/assets/85984423/96c5973c-36e3-469a-bb89-f4ddf7979b96)

