# CS370-IntelligentAgent
This repository contains my assignments, projects, and experiments completed for CS-370 at Southern New Hampshire University.
The course explores how artificial intelligence (AI), machine learning, and deep learning techniques can be applied to real-world problems. Each project builds toward understanding how intelligent agents learn from data, adapt to new environments, and make autonomous decisions.

## Brief Explanation of the Work
Throughout this course, I worked on developing and training intelligent agents using reinforcement learning concepts such as Q-Learning and Deep Q-Learning.The starter code for the project included the code that sets up an 8x8 maze, pre-defined class structures for storing episodic experience, and some helper functions for managing state transitions and rewards. I implemented the learning algorithm, defining the logic for the Q-Learning model, training loop, and neural network architecture. I found that I was unable to successfully run a neural network using Tensorflow/Keras, likely because Tensorflow did not carry support for my hardware which resulted in training taking hours to perform. To address the issue, I adapted the code to run Pytorch instead and saw significanly better performance. To enhance the training, we utilized epsilon decay which allowed for greater initial exploration, and backwards learning to greater refine the model across each epoch. For training, we allowed for a maximum of 1000 epochs, but saw training complete with a 100% win rate after 393 epochs at 6.36 minutes. From there, we successfully executed the completion_check and play_game methods to prove that the maze is valid for gameplay and that the training results in a the pirate agent successfully navigating the maze to the treasure cell.

## What Do Computer Scientists Do and Why Does It Matter?
Computer scientists design and build systems that help people solve complex problems more efficiently. Their work combines logic, creativity, and engineering to turn ideas into algorithms, models, and applications that impact nearly every part of modern life. Whether it’s developing intelligent agents, optimizing logistics networks, securing information, or improving healthcare outcomes through data analysis, computer scientists create the technology that drives progress.
What makes their work so important is its reach and responsibility. The solutions computer scientists build don’t stay in a lab, they shape how people live, work, and interact. A breakthrough in artificial intelligence, for example, can automate warehouse operations, detect disease earlier, or make vehicles safer on the road. At the same time, these technologies can raise new challenges, such as job displacement, data misuse, or biased algorithms. This balance between innovation and responsibility is what makes computer science such a powerful and influential field.

## How Computer Scientists Approach Problems
Computer scientists approach problems by breaking them down into smaller, logical parts and solving each one step by step. The process usually starts with defining what needs to be accomplished, then researching, testing, and refining different approaches until the solution works well. It involves creativity, persistence, and attention to detail. Whether building a machine learning model or debugging a piece of code, the goal is to find solutions that are efficient, reliable, and aligned with real-world needs.

## What Are My Ethical Responsibilities to the End User and the Organization?
As a computer scientist, I have a responsibility to create technology that is fair, transparent, and safe for the people who use it. Every design choice and data decision can have real-world effects.
When ethical best practices are ignored, the consequences can be serious.
* Biased outcomes: Algorithms trained on unbalanced data can make unfair decisions that harm certain groups of people.
* Privacy risks: Collecting or storing user data without strong protections can lead to breaches and loss of trust.
* Blind trust in automation: Systems that act without oversight can make poor or unsafe decisions if they are not properly tested or explained.
* Reputation damage: Ethical mistakes can hurt both users and the organization that deploys the technology.

To prevent these issues, I believe in designing systems that are open to review, tested for fairness, and built with accountability in mind. Protecting users and maintaining trust are just as important as achieving performance or efficiency.
