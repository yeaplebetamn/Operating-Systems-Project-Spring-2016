# Operating-Systems-Project-Spring-2016
You are going to write a program that simulates an operating system. Your operating system is to be designed to run on a computer with the following hardware specifications:  It has 16Mb of RAM A timeslice occurs every second. A fetch-execute-check interrupt cycle takes 0.1 seconds. An I/O operation takes somewhere between 25 to 50 cycles. The following features must be included in the operating system simulation:  The use of Process Control Blocks. They need to record I/O request information. The movement of a set of at most 60 processes through the five state model. The use of a clearly indicated, standard method for process scheduling Preemptive multitasking Interrupt handling. Process sizes will vary from 1Mb to 8Mb in size. A process must reside completely in memory before it can execute. A process will have between 0 and 5 I/O requests. A process will take between 10 and 950 cycles to complete. Processes will arrive over a period of time. The output for the program should:  Display memory - showing all processes and where they are in memory. Show all states and the processes that are in each state. For each active process the following information should be displayed: amount of CPU time needed to complete amount of CPU time already used priority (if relevant) number of I/O requests satisfied number of outstanding I/O requests This display should change each time one of the following occurs: a new process enters the system a processes state changes an I/O request is made an I/O request is completed memory is allocated or deallocated a process exits the system The display should allow me to step through each change. Do not make me press a key for every clock tick and/or timeslice! Allow me (at any time) to tell the program to run to completion and watch the changes on the screen (i.e. the changes to the screen in this mode should occur at a reasonable pace!)
