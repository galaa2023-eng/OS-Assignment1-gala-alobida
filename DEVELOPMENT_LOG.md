# Development Log

## Instructions
Document your development process as you work on the assignment. Add entries showing:
- What you worked on
- Problems you encountered
- How you solved them
- Time spent

**Requirements**: Minimum 5 entries showing progression over time.

---

## Example Entry Format:
Entry 1 - [April 1, 2026, 2:30 PM]



What I did: Forked the repository and set up my student ID

Details:

Created GitHub account with university email

Forked the starter repository

Changed student ID on line 92 to my actual ID (441234567)

Compiled and ran the program successfully

Challenges: Had to install JDK first because javac wasn't recognized

Solution: Downloaded JDK 17 from Oracle website and set PATH variable

Time spent: 30 minutes


---

## Your Development Log:
### Entry 1 - [March 28, 2026, 4:00 PM]
**What I did**: was create my environment and fork the repository

**Details**: Forked the assignment starting code and made a GitHub account. I made the necessary updates to the student ID in the source file.


**Challenges**:At first, my terminal could not recognize the javac command.

**Solution**:Set up the System Environment Variables (PATH) and installed JDK 21.

**Time spent**: 40 minutes were spent

---

### Entry 2 - [[March 28, 2026, 6:00 PM]
**What I did**: was compile the scheduling simulation and run it.


**Details**: he Java files were compiled using the terminal, and the application was run to view the Round-Robin output.

**Challenges**: It was difficult to comprehend the thread statuses because the output was scrolling too quickly.


**Solution**:In order to thoroughly examine the output, I used java Main > output.txt to reroute it to a text file.
 

**Time spent**: Thirty minutes were spent.

---

### Entry 3 - [March 29, 2026, 2:30 PM]
**What I did**:  was examine quantum behavior and thread states.

**Details**: Examined the behavior of P1 through P10 using the 4000 ms quantum. noticed when they gave over the CPU.

**Challenges**: Perplexed by the Round-Robin context's "Waiting" and "Ready" phases.

**Solution**: I discovered that returning to the Waiting/Ready queue is represented by "Yielding" in my output.


**Time spent**: 45 minutes were spent.

---

### Entry 4 - [March 30, 2026, 1:00 AM]
**What I did**: was write responses for ANSWERS.md.

**Details**:  Responded to inquiries regarding Thread vs. Process and practical uses (Streaming/Web Servers).


**Challenges**:  Meeting the "3-line" personal preference while maintaining succinct responses.


**Solution**: I used direct examples from my particular output, such as the 22 context shifts, along with bullet points.

**Time spent**: 50 minutes were spent.

---

### Entry 5 - [March 30, 2026, 4:00 AM]
**What I did**: Summary and Final Review (Reflection).

**Details**:  Finished summarizing the main ideas that were comprehended and the areas that needed further research.

**Challenges**: Making sure the reflection matched the real simulation data was one of the challenges.

**Solution**: To verify the Termination state logic, cross-referenced the "Remaining time: 0ms" logs.


**Time spent**: 
Twenty minutes were spent.

---

### Entry 6 - [Optional - Date and Time]
**What I did**: 

**Details**: 

**Challenges**: 

**Solution**: 

**Time spent**: 

---

## Summary

**Total time spent on assignment**: [3 hours]

**Most challenging part**: The hardest aspect is figuring out when a thread changes from "Running" to "Waiting" after a context switch.


**Most interesting learning**: The most fascinating thing I learned was how a little time quantum (4000 ms) gives the impression that ten threads are multitasking.

**What I would do differently next time**: the next time: I would try altering the code's quantum size to observe how it impacts the quantity of context switches.
