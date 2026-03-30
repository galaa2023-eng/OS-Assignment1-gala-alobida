# Assignment Questions

## Instructions
Answer all 4 questions with detailed explanations. Each answer should be **3-5 sentences minimum** and demonstrate your understanding of the concepts.

---

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes?

**Your Answer:While threads share resources, processes are separate entities with private memory.
Using threads speeds up job switching and lowers creation overhead.
This made it simple for us to track global variables like context switches and share data.**

[Write your answer here. Consider: What is a process? What is a thread? How do they differ in terms of memory, resources, creation overhead? Why are threads more suitable for this simulation?]

---

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from your program output.

**Your Answer:A process is preempted and pushed to the back when it exceeds its quantum.
To guarantee equity for all, the scheduler then selects the subsequent procedure.
Until every process has completed all of the necessary execution time, this cycle is repeated.**

[Write your answer here. Describe the specific behavior - where does the process go? When does it run again? Give an example from your actual program output showing a process that was re-queued.]

Example from my output:[P10] finished execution!
Ready Queue [P2, P3, P4, P5, P6, P7, P8, P9]
P1 executing quantum [2572ms]
```
[Paste a relevant snippet from your program output here showing a process being re-queued]
```

**Explanation of example:The scheduler pulled P1 from the top of the queue as soon as P10 was done.
This illustrates how the queue maintains order and advances processes to execution.
The scheduler rotates over this list to make sure no process waits indefinitely.**
[Explain what's happening in the output snippet you pasted]

---

## Question 3: Thread States

**Question**: New: When the program starts and says "P1 added to ready queue" for the first time.

Runnable: When P1 is in the "Ready Queue [P2, P3...]" waiting for its turn to execute.

Running: When the output specifically shows "P1 executing quantum [4000ms]" and the progress bar starts.

Waiting: When "P1 yields CPU for context switch" because its 4000ms ended but it has "Remaining time" left.

Terminated: When the output confirms "P1 finished execution!" because its "Remaining time: 0ms".



## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. Explain why this scheduling algorithm works well for those scenarios.

**Your Answer:**

### Example 1: First example: Web servers
**Description** To guarantee prompt responses, threads manage numerous user requests at once.
**Why Round-Robin works well here**: It uses the 4000ms quantum to stop any one big request from blocking others.
This keeps the server responsive for everyone by guaranteeing that each user receives a "slice" of CPU time.

### Example 2: Video Streaming Apps
**Description** ideo playing, UI changes, and data buffering are all handled concurrently by threads.
**Why Round-Robin works well here**: To make sure the video plays without freezing, the scheduler switches between threads.
The user views all jobs as operating simultaneously and without latency when they switch quickly.

---

## Summary

**Key concepts I understood through these questions:**
1. Processes vs. Threads: Because threads have less overhead and facilitate resource sharing, they are more efficient.
2. Round-Robin Scheduling: By alternating between processes in the ready queue, the 4000ms quantum guarantees equity.
3. Thread States: Monitoring a thread's transition from New to Running to Terminated when there is no more time.


**Concepts I need to study more:**
1. Context Switching Overhead: How the system's overall performance is affected by the frequency of switches (22 in my example).

2. Priority Inversion: The way a Round-Robin queue interacts with various priority levels (1–5 in my output).
