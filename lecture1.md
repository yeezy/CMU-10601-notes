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
    