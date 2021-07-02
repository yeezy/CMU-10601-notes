Machine learning:
study of algorithms that improve their performance - p
at some task T
with experience E

well-defined learning task: <P,T,E>
example: playing Go
task - learn to move
performance - win
experience - study experts

example: learning to drive

Current examples: CV, Speech recognition, chess, irobot, etc

Many algorithms:
•Decision trees
•Deep neural networks
•Bayesian networks
•Hidden Markov models
•Gaussian mixture model
•Expectation maximization

Machine Learning Theory:
PAC Learning Theory (supervised concept learning)


other theories for:
    reinforcement skill learning
    semi-supervised learning
    active student querying
    ...
Also relating:
    VC dimension
    asymptotic performance
    computational demands
    convergence rate
    # of mistakes during learning


Social Impacts of Machine Learning
    better evidence-based decision making in many domains
        medical diagnosis
        cc fraud detection
        online tutoring
        failure rate on devices
    controversial uses
        jail sentencing
        targeted marketing

Privacy enhanced machine learning
    Sometimes need personal data to train needed classifiers

    Homomorphic encryption
        compute average GPA students in our class
        encrypt data but perform math operations without decrypting
        given numbers n1, n2, calculate sum n1+n2 even if encrypted
        not every function can be done on encypted data
    
    Differential privacy
        add noise to data D or algorithm A, so that an observer of A's output probably
        cannot determine whether data enty D was even included in D
        Trades privacy for accuracy

This course will cover:
    Algorithms:
        Decision trees
        Bayes classifiers
        Regression
        Deep neural networks
        Convolutional nets
        Transformer networks
        Graphical models
        Expectation maximization
        PCA, Matrix factorization
        Reinforcement learning
    
    Concepts:
        Statistical estimation
        Overfitting
        Cross-validation
        Representation learning
        Probalistic models
        Proabably approximately correct learning
        VC dimension
        Role of unlabeled data
        Transfer learning
        Optimization

Machine Learning
    Statistics
        Probability
            Computer Science
                Optimization

Well Posed Learning Problems
    Three components: <T,P,E>
    Task, Performance measure, Experience

    Definition of learning:
        *a computer program learns if its performance in T improves with experience*
    
    Example tasks:
        identify objects in an image
        translate languages
        recognize speech
        assess risk in loan application
        make decisions
        assess potential

Recommended reading
    http://mlcourse.org/
    Machine Learning - TOm 
    Pattern Recognition - Christopher M Bishop
    Machine Learning - Kevin P Murphy
    The elements of statistical learning - springer, trevor hastle

Homework
    3 written assignments
    6 written + coding


Prerequisites
    Significant coding experience
    Probability and statistics
    Mathematical maturity
    Discrete mathematics
    Linear algebra
    Calculus

Supervised Classification
    Naive Bayes
    p(y|x1,x2,...,xn)=1Zp(y)n

    Logistic regression

ML Theory
    Sample complexity

Deep Learning
    Deep bi-directional RNN

Graphical Models
    Hidden Markov Model
    Conditional Random Field

Learning Objectives
    1.Formulate a well-posed learning problem for a real-world task by identifying the task, performance measure, and training experience
    2.Describe common learning paradigms in terms of the type of data available, when it’s available, the form of prediction, and the structure of the output prediction
    3.Implement Decision Tree training and prediction (w/simple scoring function)
    4.Explain the difference between memorization and generalization [CIML]
    5.Identify examples of the ethical responsibilities of an ML expert