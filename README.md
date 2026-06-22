<h1 align="center">CSE0613311 - Artificial Intelligence</h1>

- [1. Introduction to Artificial Intelligence:](#1-introduction-to-artificial-intelligence)
  - [1.1. What is AI:](#11-what-is-ai)
  - [1.2. Main Goals of AI:](#12-main-goals-of-ai)
  - [1.3. Why AI:](#13-why-ai)
  - [1.4. Foundation of AI:](#14-foundation-of-ai)
  - [1.5. A Short History of AI:](#15-a-short-history-of-ai)
  - [1.6. What Can AI Do:](#16-what-can-ai-do)
  - [1.7. What Can’t AI Systems Do Yet:](#17-what-cant-ai-systems-do-yet)
  - [1.8. Big Questions:](#18-big-questions)
  - [1.9. Who Does AI:](#19-who-does-ai)
  - [1.10. Four Goals of AI:](#110-four-goals-of-ai)
  - [1.11. What is Turing Test \& Loebner Test:](#111-what-is-turing-test--loebner-test)
  - [1.12. Purpose of Turing Test \& Loebner Test:](#112-purpose-of-turing-test--loebner-test)
  - [1.13. How Turing Test \& Loebner Test Work:](#113-how-turing-test--loebner-test-work)
  - [1.14. What is Heuristic System:](#114-what-is-heuristic-system)
  - [1.15. Reasoning Areas Where AI is Used:](#115-reasoning-areas-where-ai-is-used)
  - [1.16. Strong AI vs Weak AI:](#116-strong-ai-vs-weak-ai)
- [2. Agent and Environment:](#2-agent-and-environment)
  - [2.1. What is Agent:](#21-what-is-agent)
  - [2.2. Rationality and Autonomy:](#22-rationality-and-autonomy)
    - [2.2.1. Rationality:](#221-rationality)
    - [2.2.2. Autonomy:](#222-autonomy)
  - [2.3. Types of Agents:](#23-types-of-agents)
    - [2.3.1. Simple Reflex Agent:](#231-simple-reflex-agent)
    - [2.3.2. Model-Based Reflex Agent:](#232-model-based-reflex-agent)
    - [2.3.3. Goal-Based Agent:](#233-goal-based-agent)
    - [2.3.4. Utility-Based Agent:](#234-utility-based-agent)
    - [2.3.5. Learning Agent:](#235-learning-agent)
  - [2.4. Properties of Environments:](#24-properties-of-environments)
- [3. Home Work 1:](#3-home-work-1)
  - [3.1. Question 1:](#31-question-1)
    - [3.1.1. Answer:](#311-answer)
  - [3.2. Question 2:](#32-question-2)
    - [3.2.1. Answer:](#321-answer)
  - [3.3. Question 3:](#33-question-3)
    - [3.3.1. Answer:](#331-answer)

# 1. Introduction to Artificial Intelligence:

## 1.1. What is AI:
Artificial Intelligence (AI) is a branch of computer science that creates systems that capable of learning, reasoning, problem-solving, and making decisions in ways that normally require human intelligence.


## 1.2. Main Goals of AI: 

- Learning
- Reasoning
- Problem-Solving
- Perception
- Natural Language Understanding
- Decision-Making
- Automation
- Creating Intelligent Agents

## 1.3. Why AI:
- Automation: Automates repetitive and time-consuming tasks.
- Efficiency: Performs tasks faster and more efficiently than humans.
- Accuracy: Reduces human errors and improves consistency.
- Data Analysis: Processes and analyzes large amounts of data to find useful insights.
- Decision-Making: Helps humans make better decisions by providing intelligent recommendations.

## 1.4. Foundation of AI:
- Computer Science & Engineering
- Mathematics
- Psychology & Cognitive Science
- Philosophy
- Biology
- Neuroscience
- Linguistics
- economics


## 1.5. A Short History of AI:
| Year          | Milestone                           |
| ------------- | ----------------------------------- |
| 1943          | First artificial neuron model       |
| 1950          | Turing Test proposed                |
| 1956          | Birth of AI at Dartmouth Conference |
| 1970s–1980s   | Expert Systems                      |
| 1988–1993     | AI Winter                           |
| 1990s         | Statistical AI                      |
| 2010s–Present | Deep Learning & Generative AI       |


## 1.6. What Can AI Do:
- Learn from data
- Solve problems
- Understand language
- Recognize images and speech
- Make decisions
- Automate tasks
- Make predictions


## 1.7. What Can’t AI Systems Do Yet:

- Truly understand like humans.
- Possess consciousness or self-awareness.
- Think and reason like humans in every situation.
- Make perfect decisions.
- Fully replace humans.


## 1.8. Big Questions: 

![alt text](./assets/images/introduction-to-ai/big-questions.png)


| Question                           | Simple Answer                                                                                                      |
| ---------------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| Can machines think?                | AI researchers debate this; machines can perform intelligent tasks, but whether they truly think is controversial. |
| If so, how?                        | By processing information, learning from data, and making decisions using algorithms.                              |
| If not, why not?                   | Because they lack consciousness, emotions, and true understanding.                                                 |
| What does this say about humans?   | It helps us understand what makes human intelligence unique.                                                       |
| What does this say about the mind? | It raises questions about whether the mind works like a computer and whether consciousness can be replicated.      |


## 1.9. Who Does AI:

- AI researchers / scientists: Design new AI theories, algorithms, and models to improve intelligence systems.
- Software engineers: Build and implement AI applications and turn research ideas into real-world software.
- Data scientists: Collect, clean, and analyze data to train AI models and improve their accuracy.
- Technology companies: Develop, deploy, and scale AI products for real users (apps, services, tools).
- Universities and research labs: Conduct academic research, discover new AI methods, and train future experts.

## 1.10. Four Goals of AI:
- Learning: Enable machines to learn from data and improve performance over time.
- Reasoning: Allow machines to make logical decisions based on available information.
- Problem Solving: Help machines find solutions to complex or real-world problems.
- Perception: Enable machines to understand and interpret input from the environment (images, sound, text).


## 1.11. What is Turing Test & Loebner Test: 

- Turing Test: The Turing Test was proposed by Alan Turing. It is a test to check whether a machine can show human-like intelligence in conversation.
- Loebner Test: The Loebner Test (Loebner Prize Competition) is a real-world version of the Turing Test. Means it is an annual competition where judges interact with both humans and AI chat systems.

## 1.12. Purpose of Turing Test & Loebner Test:

- Turing Test: To evaluate whether a machine can imitate human intelligence well enough to be indistinguishable from a human in conversation.
- Loebner Test: To measure how closely AI can simulate human conversation in practice.

## 1.13. How Turing Test & Loebner Test Work:
- Turing Test: A human judge chats with two hidden participants: one human and one machine (AI). If the judge cannot reliably tell which one is the machine, the AI is said to pass the test.
- Loebner Test: Judges have conversations and try to identify which participant is the machine. The AI that most closely mimics human conversation performs best.


## 1.14. What is Heuristic System: 
A heuristic system is an AI approach that solves problems using experience-based rules or “rules of thumb” instead of trying every possible solution. For example: 
- In chess AI, instead of analyzing every possible move, the system uses heuristics to choose strong moves quickly.
- In GPS navigation, it quickly finds a good route instead of checking all possible routes.

## 1.15. Reasoning Areas Where AI is Used: 
- Medical diagnosis (finding diseases)
- Expert systems (decision support in law, finance, medicine)
- Game playing (chess, strategy games)
- Planning & scheduling (delivery routes, logistics)
- Natural language reasoning (chatbots, Q&A systems)

## 1.16. Strong AI vs Weak AI: 
| Feature       | Weak AI               | Strong AI                              |
| ------------- | --------------------- | -------------------------------------- |
| Scope         | Limited tasks         | Any task like humans                   |
| Intelligence  | Narrow                | General                                |
| Understanding | No real understanding | Human-like understanding (theoretical) |
| Existence     | Exists today          | Not yet built                          |

# 2. Agent and Environment:
## 2.1. What is Agent: 
An agent is anything that can perceive its environment through sensors and act upon that environment through actuators to achieve a goal. For examples:
- Human: Eyes and ears (sensors), hands and legs (actuators).
- Robot: Cameras and sensors (sensors), motors and wheels (actuators).
- AI Software: Input data (sensors), generated outputs or actions (actuators).

## 2.2. Rationality and Autonomy:
### 2.2.1. Rationality: 
A rational agent chooses the action that is expected to achieve the best outcome based on its knowledge and goals. For example: 
- A GPS navigation system selects the shortest or fastest route to a destination.

### 2.2.2. Autonomy: 
Autonomy is the ability of an agent to operate independently without constant human intervention. For example: 
- A self-driving car can make driving decisions on its own.

Note: There are two Levels of Autonomy:
1. Low autonomy: Requires frequent human control.
2. High autonomy: Makes most decisions independently.

## 2.3. Types of Agents:
1. Simple Reflex Agent: 
2. Model-Based Reflex Agent
3. Goal-Based Agent
4. Utility-Based Agent
5. Learning Agent

### 2.3.1. Simple Reflex Agent:
Acts only on the current percept using condition-action rules.

Example: 
- If room is dirty → Vacuum.
- If room is clean → Do nothing.

Characteristics:
- No memory
- No knowledge of past states

### 2.3.2. Model-Based Reflex Agent:
Maintains an internal model (memory) of the environment.

Example:
- A robot remembers which rooms it has already cleaned.

Characteristics:
- Uses current percept + internal state
- Better than simple reflex agents

### 2.3.3. Goal-Based Agent:
Chooses actions based on achieving specific goals.

Example:
- A navigation system finding a route to a destination.

Characteristics:
- Considers future outcomes
- Uses search and planning

### 2.3.4. Utility-Based Agent:
Chooses actions that maximize a utility (preference) measure.

Example:
- A ride-sharing app choosing the fastest and cheapest route.

Characteristics:
- Evaluates multiple possible outcomes
- Selects the most beneficial one

### 2.3.5. Learning Agent:
Improves performance through experience.

Example:
- A spam filter that becomes better at detecting spam emails over time.

Characteristics:
- Learns from data and feedback
- Adapts to new situations

## 2.4. Properties of Environments: 
The environment in which an agent operates can be described using several properties such as: 
1. Fully Observable vs Partially Observable:
   - Fully observable: Agent can perceive the complete state of the environment. For example: chess game.
   - Partially observable: Agent cannot see the entire environment.. For example: poker game.
2. Deterministic vs Stochastic:
   - Deterministic: Actions always produce predictable results. For example: Solving a math problem
   - Stochastic: Actions may have uncertain outcomes. For example: Weather forecasting
3. Episodic vs Sequential:
   - Episodic: Each decision is independent. For example: Image classification.
   - Sequential: Current decisions affect future decisions. For example: Chess. 
4. Static vs Dynamic:
   - Static: Environment does not change while the agent is making decisions. For example: Crossword puzzle.
   - Dynamic: Environment can change during decision-making. For example: Driving a car.
5. Discrete vs Continuous:
   - Discrete: Finite number of states and actions. For example: Chess.
   - Continuous: Infinite range of states or actions. For example: Autonomous driving.
6. Single-Agent vs Multi-Agent:
   - Single-Agent: Only one agent operates in the environment. For example: Sudoku solver.
   - Multi-Agent: Multiple agents interact with each other. For example: Football game.





# 3. Home Work 1:
## 3.1. Question 1: 
![alt text](./assets/images/home-work-1/question-1.png) 

![alt text](./assets/images/home-work-1/q1.png)

**Note:** Mama if you look closely to the graph you will see a pattern like this: 

```
START → A (2)
START → B (3)
START → D (5)
A → C (4)
B → D (4)
C → D (1)
C → G (2)
D → G (5)
```

and here our goal is to try to resolve the graph in such a way that states with earlier alphabetical order and expanded first.

### 3.1.1. Answer:

- Depth-First Search:  

![alt text](./assets/images/home-work-1/dfs.png)

- Breadth-First Search:

![alt text](./assets/images/home-work-1/bfs.png)

- Uniform Cost Search:

![alt text](./assets/images/home-work-1/ucs.png)

## 3.2. Question 2: 

![alt text](./assets/images/home-work-1/q2.png)
### 3.2.1. Answer:
![alt text](./assets/images/home-work-1/properties-of-dfs-bfs-ids.png)

## 3.3. Question 3:
Briefly explain the main idea behind IDS & DLS search algorithms

### 3.3.1. Answer:
![alt text](./assets/images/home-work-1/dls.png)
![alt text](./assets/images/home-work-1/ids.png)