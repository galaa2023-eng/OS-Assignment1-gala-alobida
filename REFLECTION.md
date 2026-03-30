# Reflection Questions

## Instructions
Answer the following questions about your learning experience. Each answer should be **at least 5-7 sentences** and show your understanding.

---

## Question 1: What did you learn about multithreading?

**Your Answer:I discovered that multithreading is an effective way to achieve concurrency in a single program. Seeing how threads share memory while using the run() method to independently carry out their own logic was fascinating. I also came to understand how crucial "Time Quanta" is to avoiding hunger because, in the absence of an appropriate scheduling algorithm like Round-Robin, a single long thread could cause the system to freeze. By demonstrating how the CPU switches between jobs to give the impression of simultaneous execution, this assignment brought the abstract idea of "context switching" to life.**

[Write your answer here. Discuss specific concepts like thread creation, thread states, how threads execute concurrently, what surprised you, etc.]

---

## Question 2: What was the most challenging part of this assignment?

**Your Answer:Accurately implementing Feature 3 (Waiting Time) was the hardest part. The discrepancy between a process's actual execution time and the overall amount of time it spent in the system has to be carefully calculated. Additionally, I encountered a technical difficulty when my terminal showed issues because of color formatting (Colors.PURPLE). This experience taught me that sometimes "clean" code and cross-platform compatibility are more crucial than aesthetics. Another logical challenge I had to conquer was debugging the Context Switch counter to make sure it only increased during actual process swaps.**

[Describe the specific challenge. Was it understanding the code? Implementing a feature? Using Git? Explain what made it difficult and how it relates to the course concepts.]

---

## Question 3: How did you overcome the challenges you faced?

**Your Answer:I used a combination of methodical troubleshooting and reading documentation to overcome these obstacles. I streamlined the code to prioritize functional correctness when the color mistakes started to show. To make sure the math was accurate, I tracked variable values like creationTime and remainingTime at each stage using System.out.println instructions. In order to avoid feeling overburdened and to enable me to thoroughly test each component before going on to the next, I also divided the task into tiny, manageable milestones, concentrating on one feature at a time.**

[Describe your problem-solving approach. Did you read documentation? Ask for help? Debug systematically? What resources did you use? What strategies worked?]

---

## Question 4: How can you apply multithreading concepts in real-world applications?

**Your Answer:In contemporary mobile applications, such as WhatsApp, where one thread manages the user interface (typing) and another thread downloads images in the background, multithreading is crucial. The application would freeze each time it attempted to connect to the internet if threads weren't present. Similar to this, different threads manage visuals, audio, and physics simultaneously in video games to deliver a fluid 60 frames per second. Knowing these ideas makes it easier for me to understand how software can continue to function responsively even when it is carrying out demanding background duties.**

[Give specific examples from real applications you use (web browsers, games, mobile apps, etc.). Explain why threads are useful in those scenarios. Connect to what you learned in this assignment.]

---

## Additional Reflections (Optional)

### What would you like to learn more about?

[Any topics related to threading, concurrency, or operating systems that you're curious about?]

---

### How confident do you feel about multithreading concepts now?

[Rate yourself and explain: Beginner / Intermediate / Confident]

[Explain your rating - what do you understand well? What needs more practice?]

---

### Feedback on the assignment

[Any comments about the assignment? Was it helpful? Too easy/hard? Suggestions for improvement?]
