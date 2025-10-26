# CS370

Briefly explain the work that you did on this project: What code were you given? What code did you create yourself?
For this project, I was provided with starter code that included the base environment classes (TreasureMaze.py and GameExperience.py) and helper functions to define the maze grid, valid actions, and experience replay structure. These files established how the agent interacts with the maze and stores past experiences. I created and implemented the Q-training algorithm within the qtrain() function, translating pseudocode into a working deep reinforcement learning loop. This included defining the ε-greedy policy, experience replay updates, network training steps, and safety logic to prevent infinite loops. I also optimized the pseudocode block to improve training efficiency and achieve convergence, resulting in a final model that reached a 1.000 win rate.

What do computer scientists do and why does it matter?
Computer scientists design and build computational systems that solve real-world problems efficiently and reliably. Their work matters because it enables automation, data-driven decision making, and innovation across nearly every industry, from healthcare and finance to defense and education. In this project, developing an intelligent agent to autonomously navigate a maze reflects how computer scientists create adaptive systems that learn, optimize, and improve over time.

How do I approach a problem as a computer scientist?
I approach problems systematically by breaking them into smaller, logical components, analyzing available data, and using algorithms to design a solution that can be tested and refined. For this project, that meant understanding the environment dynamics, translating theoretical pseudocode into functional Python code, and iterating until the agent’s learning process stabilized. This problem-solving mindset, analyzing, modeling, coding, testing, and improving is central to computer science practice.

What are my ethical responsibilities to the end user and the organization?
As a computer scientist, my ethical responsibilities include ensuring that the systems I design are transparent, secure, and aligned with user and organizational values. I must consider how an algorithm’s decisions impact individuals and avoid introducing bias or harm through automation. In reinforcement learning and artificial intelligence projects, that also means responsibly managing data, validating results, and clearly communicating limitations so that users can trust and understand the system’s behavior.
