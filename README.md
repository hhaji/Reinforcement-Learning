# Reinforcement-Learning

---

### **Index:**
- [Course Overview](#Course-Overview)
- [Main TextBooks](#Main-TextBooks)
- [Slides and Papers](#Slides-and-Papers)
  1. Lecture 1: [Introduction to Reinforcement Learning](#Introduction) 
  2. Lecture 2: [Exploration and Exploitation](#ExplorExploit) 
  3. Lecture 3: [Finite Markov Decision Processes](#Finite-M)
  4. Lecture 4: [Dynamic Programming](#DynamicP) 
  5. Lecture 5: [Monte Carlo Methods](#MonteCM)  
  6. Lecture 6: [Temporal-Diference Learning](#TemporalD) 
  7. Lecture 7: [n-step Bootstrapping](#Bootstrapping)   
  8. Lecture 8: [Planning and Learning with Tabular Methods](#Planning) 
  9. Lecture 9: [On-policy Prediction with Approximation](#On-policyP) 
  10. Lecture 10: [On-policy Control with Approximation](#On-policyC) 
  11. Lecture 11: [Off-policy Methods with Approximation](#Off-policy)
  12. Lecture 12: [Eligibility Traces](#Eligibility) 
  13. Lecture 13: [Policy Gradient Methods](#Gradient)  
  14. Lecture 14: [Deep Reinforcement Learning](#DRL) 
  15. Lecture 15: [Applications](#Applications) 
- [Additional Resources](#ANAS)
- [Class Time and Location](#Class-Time-and-Location)
  - [Recitation and Assignments](#MTA)  
- [Projects](#Projects)
  - [Google Colab](#Google-Colab)
  - [Fascinating Guides For Machine Learning](#Fascinating-Guides-For-Machine-Learning)
  - [Latex](#Latex)
- [Grading](#Grading)
  - [Three Exams](#Three-Exams)
- [Prerequisites](#Prerequisites)
  - [Linear Algebra](#Linear-Algebra)
  - [Probability and Statistics](#Probability-and-Statistics)
- [Topics](#Topics)
- [Account](#Account)
- [Academic Honor Code](#Academic-Honor-Code)
- [Questions](#Questions)
- Miscellaneous: 
     * [Data Handling](https://github.com/hhaji/Deep-Learning/tree/master/Data-Handling)  

---

## <a name="Course-Overview"></a>Course Overview:
```javascript
In this course, you will learn the foundations of Reinforcement Learning. To realize the dreams and impact of AI requires autonomous systems that learn to make good decisions. Reinforcement learning is one powerful paradigm for doing so, and it is relevant to an enormous range of tasks, including robotics, game playing, consumer modeling and healthcare.   
```

## <a name="Main-TextBooks"></a>Main TextBook:
![Book 1](/Images/RL.jpg)  

```
Main TextBook:
```

* [Reinforcement Learning](https://mitpress.mit.edu/books/reinforcement-learning-second-edition) by By Richard S. Sutton and Andrew G. Barto       
   

## <a name="Slides-and-Papers"></a>Slides and Papers:  
  Recommended Slides & Papers:

---

1. ### <a name="Introduction"></a>Introduction to Reinforcement Learning   
  
```
Required Reading:
```

* Slide: [Introduction](https://storage.googleapis.com/deepmind-media/UCL%20x%20DeepMind%202021/Lecture%201%20-%20introduction.pdf) by Hado van Hasselt     
 
```
Suggested Reading:
```
 
* Blog: [An Introduction to Reinforcement Learning](https://www.freecodecamp.org/news/an-introduction-to-reinforcement-learning-4339519de419/) by Thomas Simonini  
* Blog: [Reinforcement Learning Introduction: Foundations and Applications](https://blog.dominodatalab.com/introduction-to-reinforcement-learning-foundations) by  Nikolay Manchev    

```
Additional Resources:
```
 
* Toolkit: [Gym](https://gym.openai.com/) is a toolkit for developing and comparing reinforcement learning algorithms. It supports teaching agents everything from walking to playing games like Pong or Pinball.  
  - Blog: [Algorithms](https://gym.openai.com/envs/#algorithmic)
  - Blog: [Classic Control](https://gym.openai.com/envs/#classic_control)
  - Blog: [Robotics](https://gym.openai.com/envs/#robotics)
  - Blog: [MuJoCo](https://gym.openai.com/envs/#mujoco)
  - Blog: [Atari](https://gym.openai.com/envs/#atari)
* Blog: [Reinforcement Learning Tutorial](https://www.javatpoint.com/reinforcement-learning)   
* Blog: [Reinforcement Learning: What is, Algorithms, Types & Examples](https://www.guru99.com/reinforcement-learning-tutorial.html) by Daniel Johnson   
* Blog: [The Unsupervised Reinforcement Learning Benchmark](https://bair.berkeley.edu/blog/2021/12/15/unsupervised-rl/) by Misha Laskin and Denis Yarats   
  
2. ### <a name="ExplorExploit"></a>Exploration and Exploitation   

```
Required Reading:
```

  * Slide: [Exploration and Exploitation](https://storage.googleapis.com/deepmind-media/UCL%20x%20DeepMind%202021/Lecture%202-%20Exploration%20and%20control_slides.pdf) by Hado van Hasselt   
  * Paper: [A Tutorial on Thompson Sampling](https://arxiv.org/pdf/1707.02038.pdf) by Daniel J. Russo, Benjamin Van Roy, Abbas Kazerouni, Ian Osband, and Zheng Wen   
  * Lecture: [Introduction to Thompson Sampling](https://ieor8100.github.io/mab/Lecture%204.pdf) by Erik Waingarten (Instructor: Shipra Agrawal)    

```
Suggested Reading:
```

  * Blog: [Bandit Algorithms](https://banditalgs.com/) by Tor Lattimore and Csaba Szepesvari  
  * Slide: [Exploration and Exploitation](https://www.davidsilver.uk/wp-content/uploads/2020/03/XX.pdf) by David Silver  
  * Lecture: [Stochastic Multi-Armed Bandits, Regret Minimization](https://courses.cs.washington.edu/courses/cse599i/18wi/resources/lecture3/lecture3.pdf) by Walter Cai, Emisa Nategh, Jennifer Rogers (Lecturer: Kevin Jamieson) 
  * Blog: [Beta Distribution — Intuition, Examples, and Derivation](https://towardsdatascience.com/beta-distribution-intuition-examples-and-derivation-cf00f4db57af) by Aerin Kim   
  * Blog: [Visualizing Beta Distribution and Bayesian Updating](https://towardsdatascience.com/visualizing-beta-distribution-7391c18031f1) by Shaw Lu  
  * Blog: [Conjugate Prior Explained: With Examples & Proofs](https://towardsdatascience.com/conjugate-prior-explained-75957dc80bfb) by Aerin Kim      

```
Additional Resources:
```

  * Tool: [The Calculator for Beta Distribution](https://homepage.divms.uiowa.edu/~mbognar/applets/beta.html) by Dr. Bognar    
  * Tool: [Probability Distribution Explorer:](https://distribution-explorer.github.io/index.html) This is a tool for you to explore commonly used probability distributions, including information about the stories behind them (e.g., the outcome of a coin flip is Bernoulli distributed), their probability mass/probability density functions, their moments, etc.   
  * Blog: [Learn Thompson Sampling by Building an Ad Auction!](https://www.countbayesie.com/blog/2020/9/26/learn-thompson-sampling-by-building-an-ad-auction) by Will Kurt    
  * Blog: [Do You Know Credible Interval](https://towardsdatascience.com/do-you-know-credible-interval-e5b833adf399) by Shaw Lu  
  * Toolkit: [Multi-armed Bandit Demo](https://mark.reid.name/code/bandits/) by Mark Reid   
  * Code (Python): [Reinforcement Learning: The K-armed bandit problem](https://blog.dominodatalab.com/k-armed-bandit-problem) by  Nikolay Manchev  
  * Code (Python): [Multi-Armed Bandit Python Example using UCB](https://www.hackdeploy.com/multi-armed-bandit-python-example-using-ucb/) by HackDeploy  
  * Code (Python): [Multi-Armed Bandits: Epsilon-Greedy Algorithm with Python Code](https://medium.com/analytics-vidhya/multi-armed-bandits-part-1-epsilon-greedy-algorithm-with-python-code-534b9e2abc9) by  Artemis Nika        

3. ### <a name="Finite-M"></a>Finite Markov Decision Processes         

```
Required Reading:
```

  * Slide: [MDPs & Dynamic Programming](https://storage.googleapis.com/deepmind-media/UCL%20x%20DeepMind%202021/Lecture%203%20-%20MDPs%20and%20Dynamic%20Programming.pdf) by Diana Borsa   
 
```
Suggested Reading:
```

  * Blog: [Understanding Markov Chains with the Black Friday Puzzle](https://www.countbayesie.com/blog/2015/11/21/the-black-friday-puzzle-understanding-markov-chains) by Will Kurt    
  * Blog: [The Intuition Behind Markov Chains](https://towardsdatascience.com/the-intuition-behind-markov-chains-713e6ec6ce92) by Kyle Chan   


```
Additional Resources:
```

  * Slide: [An Introduction to Markov Decision Processes](https://engineering.purdue.edu/~givan/talks/mdp-tutorial.pdf) by Bob Givan and Ron Parr    

4. ### <a name="DynamicP"></a>Dynamic Programming             

```
Required Reading:
```

  * Slide: [MDPs & Dynamic Programming](https://storage.googleapis.com/deepmind-media/UCL%20x%20DeepMind%202021/Lecture%203%20-%20MDPs%20and%20Dynamic%20Programming.pdf) by Diana Borsa   
  * Blog: [GridWorld: Dynamic Programming Demo](https://cs.stanford.edu/people/karpathy/reinforcejs/gridworld_dp.html) by Andrej Karpathy   
  * Blog: [Why Does the Optimal Policy Exist?](https://towardsdatascience.com/why-does-the-optimal-policy-exist-29f30fd51f8c) by Alireza Modirshanechi  
  * Blog: [Optimizing Jack's Car Rental](https://alexkozlov.com/post/jack-car-rental/) by Alexander Kozlov  
  * Note: [How to Gamble If You Must](https://www.maa.org/sites/default/files/pdf/joma/Volume8/Siegrist/RedBlack.pdf) by Kyle Siegrist  
  * Blog: [Hyperbolic Discounting — The Irrational Behavior That Might be Rational After All](https://chris-said.io/2018/02/04/hyperbolic-discounting/) by Chris Said 

```
Suggested Reading:
```
To get more familiar with dynamic programing, I recommend to read the following blogs:   
  * Blog: [Overlapping Subproblems Property in Dynamic Programming](https://www.geeksforgeeks.org/overlapping-subproblems-property-in-dynamic-programming-dp-1/)  
  * Blog: [Optimal Substructure Property in Dynamic Programming](https://www.geeksforgeeks.org/optimal-substructure-property-in-dynamic-programming-dp-2/)     
  * Blog: [Longest Increasing Subsequence](https://www.geeksforgeeks.org/longest-increasing-subsequence-dp-3/)      
  * Blog: [Longest Common Subsequence](https://www.geeksforgeeks.org/longest-common-subsequence-dp-4/)  

```
Additional Resources:
```

  * Algorithms: [Visualizations of Graph Algorithms:](https://algorithms.discrete.ma.tum.de/) Some important algorithms of this area are presented and explained in the following, including both an interactive applet and pseudocode.     
  * Blog: [Bellman–Ford Algorithm](https://www.geeksforgeeks.org/bellman-ford-algorithm-dp-23/)    

5. ### <a name="MonteCM"></a>Monte Carlo Methods  

```
Required Reading:
```

  * Slide: [Model-Free Prediction](https://storage.googleapis.com/deepmind-media/UCL%20x%20DeepMind%202021/Lecture%205%20-%20ModelFreePrediction.pdf) by Hado van Hasselt     
  * Blog: [Introduction to Monte Carlo Methods](https://www.datacamp.com/community/tutorials/tutorial-monte-carlo) by Asael Alonzo Matamoros  
  * Blog: [Introduction to Monte Carlo simulation](https://kinder-chen.medium.com/introduction-to-monte-carlo-simulation-156c45ad44f0) by Kinder Chen  
  * Blog: [Off Policy Monte Carlo Prediction with Importance sampling](https://shangeth.com/post/off-policy-monte-carlo/) by Shangeth Rajaa    

```
Suggested Reading:
```

  * Paper: [Monte Carlo Methods](http://reflect.otago.ac.nz/cosc453/student_tutorials/monte_carlo.pdf) by Jonathan Pengelly  
  * Blog: [What is Rejection Sampling?](https://towardsdatascience.com/what-is-rejection-sampling-1f6aff92330d) by Kapil Sachdeva   

6. ### <a name="TemporalD"></a>Temporal-Diference Learning            

```
Required Reading:
```

  * Blog: [Reinforcement Learning Tutorial Part 1: Q-Learning](https://valohai.com/blog/reinforcement-learning-tutorial-part-1-q-learning/) by Juha Kiili   

```
Suggested Reading:
```

  * Blog: [Deep Double Q-Learning — Why You Should Use It](https://medium.com/@ameetsd97/deep-double-q-learning-why-you-should-use-it-bedf660d5295) by Ameet Deshpande    
  * Blog: [5 Steps to Master the Reinforcement Learning with a Q-Learning Python Example](https://www.learnpythonwithrune.org/5-steps-to-master-the-reinforcement-learning-with-a-q-learning-python-example/) by Rune
  * Blog: [Reinforcement Learning — Generalisation of Continuing Tasks](https://towardsdatascience.com/reinforcement-learning-generalisation-on-continuing-tasks-ffb9a89d57d0) by Jeremy Zhang 


```
Additional Resources:
```

  * Blog: [Dopamine and Temporal Difference Learning: A Fruitful Relationship Between Neuroscience and AI](https://www.deepmind.com/blog/article/Dopamine-and-temporal-difference-learning-A-fruitful-relationship-between-neuroscience-and-AI) by Will Dabney and Zeb Kurth-Nelson   
  * Blog: [Temporal-Difference (TD) Learning (Using Gym)](http://christianherta.de/lehre/dataScience/machineLearning/reinforcementLearning/temporal_difference_learning.slides.php) by Christian Herta    

7. ### <a name="Bootstrapping"></a>n-step Bootstrapping               

```
Required Reading:
```

  * [Multi-step Bootstrapping](https://www.cs.mcgill.ca/~dprecup/courses/RL/Lectures/9-multistep.pdf) by Doina Precup   


8. ### <a name="Planning"></a>Planning and Learning with Tabular Methods            

```
Required Reading:
```

  * Blog: [Integrating Real and Simulated Data in Dyna-Q Algorithm](https://ranko-mosic.medium.com/online-planning-agent-dyna-q-algorithm-and-dyna-maze-example-sutton-and-barto-2016-7ad84a6dc52b) by Ranko Mosic  

```
Suggested Reading:
```

  * [Monte Carlo Tree Search – Beginners Guide](https://int8.io/monte-carlo-tree-search-beginners-guide/) by Kamil Czarnogórski    
  * Blog: [Monte Carlo Tree Search: An Introduction](https://towardsdatascience.com/monte-carlo-tree-search-an-introduction-503d8c04e168) by Benjamin Wang    
  * Blog: [Introduction to Monte Carlo Tree Search: The Game-Changing Algorithm behind DeepMind's AlphaGo](https://www.analyticsvidhya.com/blog/2019/01/monte-carlo-tree-search-introduction-algorithm-deepmind-alphago/) by Ankit Choudhary   

9. ### <a name="On-policyP"></a>On-policy Prediction with Approximation            

```
Required Reading:
```

  * Slide: [Function Approximation in Reinforcement Learning](https://storage.googleapis.com/deepmind-media/UCL%20x%20DeepMind%202021/Lecture%207-%20Function%20approximation%20in%20reinforcement%20learning%20.pdf) by  Hado van Hasselt     
  * Blog: [Tile-Coding: An Efficient Sparse-Coding Method for Real-Valued Data](https://medium.com/criteo-engineering/tile-coding-an-efficient-sparse-coding-method-for-real-valued-data-e787eddf630a) by Hamid Maei     
  * Blog: [State Aggregation with Monte Carlo](https://www.coursera.org/lecture/prediction-control-function-approximation/state-aggregation-with-monte-carlo-aJ9j6)    

```
Suggested Reading:
```

  * Blog: [Radial Basis Function Neural Network Simplified](https://towardsdatascience.com/radial-basis-function-neural-network-simplified-6f26e3d5e04d) by Luthfi Ramadhan   
  * Blog: [RBF Neural Networks](https://www.dtreg.com/solution/rbf-neural-networks)   

10. ### <a name="On-policyC"></a>On-policy Control with Approximation            

```
Required Reading:
```

  * Slide: [Function Approximation in Reinforcement Learning](https://storage.googleapis.com/deepmind-media/UCL%20x%20DeepMind%202021/Lecture%207-%20Function%20approximation%20in%20reinforcement%20learning%20.pdf) by  Hado van Hasselt    

```
Suggested Reading:
```

  * Blog: [Tile Coding Software](http://incompleteideas.net/tiles/tiles3.html) by Richard S. Sutton   
  

11. ### <a name="Off-policy"></a>Off-policy Methods with Approximation            

```
Required Reading:
```

  * Slide: [Multi-step & Off Policy](https://storage.googleapis.com/deepmind-media/UCL%20x%20DeepMind%202021/Lecture%2011-%20Off-policy%20and%20multi-step.pdf) by  Hado van Hasselt     


12. ### <a name="Eligibility"></a>Eligibility Traces             

```
Required Reading:
```

  * [Eligibility Traces](https://www.cs.utexas.edu/~pstone/Courses/394Rfall16/resources/week6-sutton.pdf) by Doina Precup   

13. ### <a name="Gradient"></a>Policy Gradient Methods          

```
Required Reading:
```

* Slide: [Policy Gradient](https://www.davidsilver.uk/wp-content/uploads/2020/03/pg.pdf) by David Silver   
* Slide: [Policy-Gradient & Actor-Critic methods](https://storage.googleapis.com/deepmind-media/UCL%20x%20DeepMind%202021/Lecture%209-%20Policy%20gradients%20and%20actor%20critics.pdf) by  Hado van Hasselt      

14. ### <a name="DRL"></a>Deep Reinforcement Learning            

```
Required Reading:
```

  * Slide: [Deep Reinforcement Learning 1](https://storage.googleapis.com/deepmind-media/UCL%20x%20DeepMind%202021/Lecture%2012-%20Deep%20RL%201%20.pdf)  by Matteo Hessel      
  * Slide: [Deep Reinforcement Learning 2](https://storage.googleapis.com/deepmind-media/UCL%20x%20DeepMind%202021/Lecture%2013%20-%20Deep%20RL%202.pdf) by Matteo Hessel      


```
Suggested Reading:
```
  
  * Blog: [Deep Reinforcement Learning: Pong from Pixels](http://karpathy.github.io/2016/05/31/rl/) by Andrej Karpathy    
  * Blog: [Reinforcement Learning with Neural Network](https://www.baeldung.com/cs/reinforcement-learning-neural-network) by Kumar Chandrakant      
  
```
Additional Resources:
```

  * Toolkit: [Welcome to Spinning Up in Deep RL!](https://spinningup.openai.com/en/latest/) This is an educational resource produced by OpenAI that makes it easier to learn about deep reinforcement learning (deep RL).  
  * Blog: [A Free course in Deep Reinforcement Learning from Beginner to Expert](https://simoninithomas.github.io/Deep_reinforcement_learning_Course/) Thomas Simonini   


15. ### <a name="Applications"></a>Applications             

```
Required Reading:
```

* Slide: [Classic Games](https://www.davidsilver.uk/wp-content/uploads/2020/03/games.pdf) by David Silver    

```
Additional Resources:
```

* Blog: [Applications](https://www.davidsilver.uk/applications/) by David Silver   
* Blog: [Emergent Tool Use from Multi-Agent Interaction](https://openai.com/blog/emergent-tool-use/) by OpenAI    
* Blog: [Solving Rubik’s Cube with a Robot Hand](https://openai.com/blog/solving-rubiks-cube/) by OpenAI    



### <a name="ANAS"></a>Additional Resources:    
- Papers:  
  * Slide: [Distributed RL](http://rail.eecs.berkeley.edu/deeprlcourse-fa19/static/slides/lec-17.pdf) by Richard Liaw   
  * PDF: [Acme: A Research Framework for Distributed Reinforcement Learning](https://arxiv.org/pdf/2006.00979.pdf)
  * Blog: [Acme: A New Framework for Distributed Reinforcement Learning](https://deepmind.com/research/publications/2020/Acme)
  * GitHub: [Must-read Papers on GNN](https://github.com/thunlp/GNNPapers#reinforcement-learning) by Natural Language Processing Lab at Tsinghua University  

- Online Demos:
  * Blog: [ConvNetJS Deep Q Learning Demo](https://cs.stanford.edu/people/karpathy/convnetjs/demo/rldemo.html) by Andrej Karpathy   
  
- Codes:
  * Codes: [Reinforcement Learning an Introduction](https://github.com/ShangtongZhang/reinforcement-learning-an-introduction) by Shangtong Zhang   

- Courses: 
  * Blog: [Reinforcement Learning Lecture Series 2021 (DeepMind)](https://deepmind.com/learning-resources/reinforcement-learning-series-2021) by Hado van Hasselt, Diana Borsa & Matteo Hessel      
  Blog: A Course taught by David Silver:     
  * [Introduction to Reinforcement Learning](https://deepmind.com/learning-resources/-introduction-reinforcement-learning-david-silver)    
  * [Reinforcement Learning](https://www.davidsilver.uk/teaching/)     

## <a name="Class-Time-and-Location"></a>Class Time and Location:
Saturday and Monday 

### <a name="MTA"></a>Recitation and Assignments:
Tuesday  

## <a name="Projects"></a>Projects:
Projects are programming assignments that cover the topic of this course. Any project is written by **[Jupyter Notebook](http://jupyter.org)**. Projects will require the use of Python 3.7, as well as additional Python libraries. 

### <a name="Google-Colab"></a>Google Colab:
[Google Colab](https://colab.research.google.com) is a free cloud service and it supports free GPU! 
  - [How to Use Google Colab](https://www.geeksforgeeks.org/how-to-use-google-colab/) by Souvik Mandal <br> 
  - [Primer for Learning Google Colab](https://medium.com/dair-ai/primer-for-learning-google-colab-bb4cabca5dd6)
  - [Deep Learning Development with Google Colab, TensorFlow, Keras & PyTorch](https://www.kdnuggets.com/2018/02/google-colab-free-gpu-tutorial-tensorflow-keras-pytorch.html)

### <a name="Fascinating-Guides-For-Machine-Learning"></a>Fascinating Guides For Machine Learning:
* [Technical Notes On Using Data Science & Artificial Intelligence: To Fight For Something That Matters](https://chrisalbon.com) by Chris Albon

### <a name="Latex"></a>Latex:
The students can include mathematical notation within markdown cells using LaTeX in their **[Jupyter Notebooks](http://jupyter.org)**.<br>
  - A Brief Introduction to LaTeX [PDF](https://www.seas.upenn.edu/~cis519/spring2018/assets/resources/latex/latex.pdf)  <br>
  - Math in LaTeX [PDF](https://www.seas.upenn.edu/~cis519/spring2018/assets/resources/latex/math.pdf) <br>
  - Sample Document [PDF](https://www.seas.upenn.edu/~cis519/spring2018/assets/resources/latex/sample.pdf) <br>
  - [TikZ:](https://github.com/PetarV-/TikZ) A collection Latex files of PGF/TikZ figures (including various neural networks) by Petar Veličković. 

## <a name="Grading"></a>Grading:
* Projects and Midterm – 50%
* Endterm – 50%

### <a name="Three-Exams"></a>ُThree Exams:

* First Midterm Examination:  
* Second Midterm Examination: 
* Final Examination:  

## <a name="Prerequisites"></a>Prerequisites:
General mathematical sophistication; and a solid understanding of Algorithms, Linear Algebra, and 
Probability Theory, at the advanced undergraduate or beginning graduate level, or equivalent.

### <a name="Linear-Algebra"></a>Linear Algebra:
* Video: Professor Gilbert Strang's [Video Lectures](https://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/video-lectures/) on linear algebra.

### <a name="Probability-and-Statistics"></a>Probability and Statistics:
* [Learn Probability and Statistics Through Interactive Visualizations:](https://seeing-theory.brown.edu/index.html#firstPage) Seeing Theory was created by Daniel Kunin while an undergraduate at Brown University. The goal of this website is to make statistics more accessible through interactive visualizations (designed using Mike Bostock’s JavaScript library D3.js).
* [Statistics and Probability:](https://stattrek.com) This website provides training and tools to help you solve statistics problems quickly, easily, and accurately - without having to ask anyone for help.
* Jupyter NoteBooks: [Introduction to Statistics](https://github.com/rouseguy/intro2stats) by Bargava
* Video: Professor John Tsitsiklis's [Video Lectures](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-041-probabilistic-systems-analysis-and-applied-probability-fall-2010/video-lectures/) on Applied Probability.
* Video: Professor Krishna Jagannathan's [Video Lectures](https://nptel.ac.in/courses/108106083/) on Probability Theory.


## <a name="Topics"></a>Topics:
Have a look at some assignments of Stanford students ([Reinforcement Learning](https://web.stanford.edu/class/cs234/assignments.html) 
to get some general inspiration.

## <a name="Account"></a>Account:
It is necessary to have a [GitHub](https://github.com/) account to share your projects. It offers 
plans for both private repositories and free accounts. Github is like the hammer in your toolbox, 
therefore, you need to have it!

## <a name="Academic-Honor-Code"></a>Academic Honor Code:
Honesty and integrity are vital elements of the academic works. All your submitted assignments must be entirely your own (or your own group's).

We will follow the standard of Department of Mathematical Sciences approach: 
* You can get help, but you MUST acknowledge the help on the work you hand in
* Failure to acknowledge your sources is a violation of the Honor Code
*  You can talk to others about the algorithm(s) to be used to solve a homework problem; as long as you then mention their name(s) on the work you submit
* You should not use code of others or be looking at code of others when you write your own: You can talk to people but have to write your own solution/code

## <a name="Questions"></a>Questions?
I will be having office hours for this course on Saturday (09:00 AM--10:00 AM). If this is not convenient, email me at hhaji@sbu.ac.ir or talk to me after class.
