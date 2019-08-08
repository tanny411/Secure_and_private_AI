## Natural Language Processing:
- https://www.youtube.com/watch?v=bDxFvr1gpSU
- From text we extract 3 things: syntax, semantics, pragmatics(context).
- Alan Turing paper : Computing Machinery and Intelligence
- Noam Chomsky Book : Syntactic structure. From here comes rule based systems in NLP.
- 1980s NLP in ML started. e.g decision trees = automatically learned if-else rules?
- Now? Deep!! 2019?! Transfer Learning!
- BERT a Language Model(Pretrained) SOTA in *11* NLP tasks. It is a transformer model.
- Talks about why language model over word2vec.
- TRANSFORMER: a newer type of NN >> all Recurrent networks. Dont use recurrents. They use *attention*.
- text classification and **extractive summarization** : https://github.com/llSourcell/bert-as-service

## Sentiment Analysis/Opinion Mining
- https://www.youtube.com/watch?v=3Pzni2yfGUQ
- Direct Opinion vs Comparative opinion.
- Explicit (good) vs implicit (heavy implies weight) opinion.
- We can perform sentiment analysis in document level, sentence level or even sub-sentence level.
- Two ways: 
	- Rule based. From a dictionary of + or - words. https://github.com/llSourcell/Sentiment_Analysis
	- NN. e.g Scikitlearn

## Privacy in DS
- https://www.youtube.com/watch?v=39hNjnhY7cY
- GDPR : set of laws protecting the EU citizens.
- **Everything about you is DATA**
- https://github.com/OpenMined/PySyft/tree/master/examples/tutorials
- Federated Learning: Users generate data. It brings the model to the training data. But we can . reverse engineer the learnt weights and learn about user data :o
- Secure Multparty Computation: Solves the above mentioned problem. Data partitioned and encrypted. Computations possible in encrypted state. 
- Differencial privacy: Makes sure a model learns only what its supposed to learn without accidentally learning private info from a dataset. Its a promise of the data scientist to the data owner.

## How to ML?
- https://www.youtube.com/watch?v=waXHrc2m9K8
- https://github.com/llSourcell/Machine_Learning_Journey
**Step - 1:**
- Lead A a healthy life. Self talk. Stop automated negative thoughts. You are NOT too old/unsmart/blah blah...
- So many reources, no excuses please!!
- Peer GROUP! Classmates, Slacks.
- Exercise! Good for heart? Good for brain!
- Eat healthy. You know why!
- Good nights rest is a MUST.
- Information overload is a real thing. Isolate from internet for sometime. Continuous 24 hour a week disconnet.
- **Step - 2:**
- Optimize learning environment. A designated place to study!(We know this from habit forming books)
- **Step - 3:**
- Personalized learning path ***
	- Diversify materials to know which suits best for you
- 100 days Of ML pledge : https://github.com/llSourcell/100_Days_of_ML_Code
- **Step - 4:**
- Priotize
- Multitasking is a MYTH (I knew it!!!)
- 4 Quadrant method!
- **Step - 5:**
- Be an active learner
- Need to be fully present
- *FAST* method:
	- **F**orget (Forget earlier assumptions about a topic)
	- **A**ctivate (not inactively being lectured to)
	- **S**tate (be in a good mood)
	- **T**each (*Learn with the intention of teaching it to someone else*)

## ML in 3 months:
- Look as hiring page for **DeepMined**
- Skills:
	- CS (ok!)
	- Python
	- ML
	- Algorithmic design
	- no PHD or numerous publications required!
- ML prerequisites:
	- 35% Linear Alg
	- 25% probability and statistics
	- 15% calculus
	- 15% Algorithm and Complexity
	- 10% Data pre-processing
- https://github.com/llSourcell/Learn_Machine_Learning_in_3_Months
- BUT... Daily... Keep up with the field!
	- ML sub-reddit
	- twitter !!!
	- HackerNews

## (The Art of) Deep Learning in 6 weeks(1.5 months???)
- https://www.youtube.com/watch?v=_qjNH1rDLm0
- Listings(for **job**)
	- AngelList
	- HackerNews
	- indeed.com
- They look for experience:
	- building
	- training
	- **deploying** DL models for real life use cases!
- A project every-week to build a portfolio in github
- Ian Goodfellow book

## How do we Democratize Access to Data?
- **Redo!** 
- https://www.youtube.com/watch?v=HAC6sqq7_-U
- OpenMined
	- deep learning
	- federated learning
	- homomorphic encryption
	- blockchain smart contracts
		- Decentralised immutable database
- https://github.com/llSourcell/OpenMined_demo
- **Challenge : Make a contribution to OpenMined!**

## 10 books
- https://www.youtube.com/watch?v=1lxHH1UBTBU&feature=youtu.be
- criteria:
	- free
	- highly reviews
	- for beginners
- Dunning-kruger effect: One aspect of low intelligence is you dont know what you dont know!
- David eagleman with Sadhguru interview.
- Harvard intro to neuro science course on Edex.
- Bayesian statictics and probabbilistic programming have a lot of real world applications such as automatic "hyperparameter fine-tuning"
- Take a look at - Pyro: Uber AI labs deep probabilistic programming language!
- Causal reasonong(being able to ask counter questions) is a huge limit in AI systems today. But if we solve it, it will make our systems mych more intelligent.
- The Future of AI involves Quantum Computing!

## Learn NLP:
- https://www.youtube.com/watch?v=GazFsfcijXQ&t=350s
- 

## Maths of ML:
- https://www.youtube.com/watch?v=8onB7rPG4Pk
- Stat, Prob, Calc, LA
- Linear and Logistic regression explained

### Github:
- https://www.youtube.com/watch?v=Loav1kbA640
- ![git workflow](https://github.com/tanny411/Secure_and_private_AI/blob/master/img/git.png)
- git init
- git config --global user.email ""
- add, commit
- checkout -b newbrach (creating and switching to the newbranch)
- add commit in newbrach
- git checkout master (switch to master)
- git merge new_branch (will have conflict if changes are in the same file)
- nano 'conflicting_file.txt' ad fix it
- then add, commit
- add remote and push
- get more people to view/contribute to your code:
	- good documentation
	- add an explainer content e.g video/blog post
- resources:
	- https://guides.github.com/activities/hello-world/
	- https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners
	- ** https://try.github.io/
	- http://kbroman.org/github_tutorial/
	- https://blog.udacity.com/2015/06/a-beginners-git-github-tutorial.html

## How to Write a research paper:
- https://www.youtube.com/watch?v=S47RIVkr978
- start by asking question, broad or specific
- try to find yourself the answers
- verify from others
- if you didnt find a answer, you found a good area for research
- start narrowing the question down
- collect your data, altho there's a large source, learn to be ctitical about what you choose. there may be biases. also .org, .edu are more reliable given .com MAY be business centric(therefore MAYBE misleading)
- papers, sources of paper
- start learning from your sources
- you will have a possible solution to your question. that is your thesis.
- thesis may change, no worries
- ask for validation of your thesis from people well-versed in your topic
- email paper authors directly, or ask in relevant social media platforms
- after validation, experiment
- start with a basic solution and then get creativeSS
- start writing an outline
- **actual paper writing starts**
- look at papers and create a list of subsections
- any extra subsectio you wanna add? or takeaway?
- **Rough draft**: add all details, add refs
- ideal length : 5-10 pages
- omnigraohol, inscrae to create graphs: always better to show
- smooth out from one topic to another
- Dont try to make it perfect on the first go. Write, re-iterate
- revise! grammar, spelling, factual errors
- submit in journal or social media or just github
- getting accepted gives your paper more technical authority

### Loss Funtions
- https://www.youtube.com/watch?v=IVVVjBSk9N0
1. cross-entropy:
- sum( -p*log(p) ) is the entropy, the info we got as bits from a sample, across all classes.
- sum( -p*log(**q**) ) the difference in predicted distribution and actual distribution. Also called cross-entropy.
- cross-entropy is paired with softmax for obvious reasons.
- cross-entropy: `np.sum( -np.log( preds[,labels] ) )/m`
2. Hinge loss:
- usually in SVMs
- our labels are either 1 or -1
- for binary classification: sum( max( 0 , 1-y*h(x) ) )
- faster. speed over accuracy? use hinge.
3. Mean squared:
- Also called l2 loss, used for regression
- mean of the square of the difference in prediction :D
- the square is there, to make our result quadratic, or convex, with a single minima.
4. Mean absolute error:
- average of the absolute of the difference in prediction
- in regression
- MAE is more robust towards outliers (because in MSE the bigger diff was being penalized too much)
5. Hubar loss:
- like mae, is lee sensitive to outliers
- quadratic for small values, and linear for large values

### Activation Function
- https://www.youtube.com/watch?v=-7scQpJT7uo
- without nonlinearities, everything will be linear :|
- line, plane, hyperplane. just linear. Less complex.
- we would like some x^2 or x^100
- NN = _universal function approximators_
- Also we want the function to be _differentiable_
- Sigmoid: [0,1], but causes gradients to vanish or explode. Plus not zero centred.
- Tanh: [-1,0], vanishing problem persists
- Relu: improved convergence. vanishing problem avoided. only for hidden layers. At some point, a neuron is turns 0, will remain zero.
- Leaky Relu: not exatly 0 for `x<0`. To not make 0 and keep the neuron alive. 
- Maxout: generalization of relu and leaky relu, but doubles the # of parameters for each neuron.

## ** Todo:
- **TPU** : https://www.youtube.com/watch?v=jgNwywYcH4w
- **Andrew Trask** : https://www.youtube.com/watch?v=qJ1rdVEcl5g
