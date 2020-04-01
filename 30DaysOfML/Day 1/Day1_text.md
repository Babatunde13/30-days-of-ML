                        ## Machine Learning
                
When most people hear “Machine Learning,” they picture a robot: a dependable butler or a deadly Terminator depending on who you ask. But Machine Learning is not just a futuristic fantasy, it’s already here. In fact, it has been around for decades in some specialized applications, such as Optical Character Recognition (OCR). But the first MLapplication that really became mainstream, improving the lives of hundreds of millions of people, took over the world back in the 1990s: it was the spam filter. Not exactly a self-aware Skynet, but it does technically qualify as Machine Learning (it has actually learned so well that you seldom need to flag an email as spam anymore). It was followed by hundreds of MLapplications that now quietly power hundreds of products and features that you use regularly, from better recommendations to voice search.

                       ## What Is Machine Learning?
Machine Learning is the science (and art) of programming computers so they can learn from data.
Here is a slightly more general definition:
[Machine Learning is the] field of study that gives computers the ability to learn without being
explicitly programmed.
Arthur Samuel, 1959

And a more engineering-oriented one:
A computer program is said to learn from experience E with respect to some task T and some
performance measure P, if its performance on T, as measured by P, improves with experience E.
Tom Mitchell, 1997

                    ## Types of Machine Learning
                    
Machine Learning can be classified based different things:

    1. Supervision
    
    2. Whether it can relearn from new data, can it run on the fly?
    
    3. Instance - Based Vs Model - Based Learning.
    
## 1. Supervision.

a. Supervised Data: Presence of labelled data 
                Regression <br/>
                Classification
                
                    Algorithms
                    1. K - Nearest Neighbour
                    2. Linear Regression
                    3. Decision Trees and Random Forest etc
                

b. Unsupervised Data: Absence of labelled data
                Clustering <br/>
                Association<br/>
                Visualisation and Dimentionality Reduction<br/>
                
                Algorithms
                1. K- means, Hierearchical Clustering
                2. Principa Component Analysis, Kernel PCA
                3. Apriori etc
                
c. Semi Supervised Learning: Few labelled data is present. <br/>

d. Reinforcement Learning <br/>

                        Batch Vs Online Learning
                
a. Batch Learning: The system is incapable of learning incrementally. It must be trained using all available data. It takes a lot of time and computing resources. It is also called offline learning. <br/>

b. Online Learning: Here the system learns incrementally by feeding it data instances sequentially either individually or by small groups called mini - batches. Online learning is great for system that receive data as continous flow e.g stock prices and to adapt to change rapidly or autonomously. It is also a good option if you have limited computing resources. LEARNING RATE is an important parameter of Online Learning.

                        Instance-Based Vs Model-Based Learning
                        
Instance-based learning: refers to a family of techniques for  classification  and  regression, which produce a class label/predication based on the similarity of the query to its nearest neighbor(s) in the training set. In explicit contrast to other methods such as  decision trees and  neural networks, instance-based learning algorithms do not create an abstraction from specific instances. Rather, they simply store all the data, and at query time derive an answer from an examination of the query’s  nearest neighbor(s).

The core idea at the heart of model-based machine learning is that all the assumptions about the problem domain are made explicit in the form of a model. In fact, a model is just made up of this set of assumptions, expressed in a precise mathematical form. These assumptions include the number and types of variables in the problem domain, which variables affect each other, and what the effect of changing one variable is on another variable. For example, in the next chapter we build a model to help us solve a simple murder mystery. The assumptions of the model include the list of suspected culprits, the possible murder weapons, and the tendency for particular weapons to be preferred by different suspects. This model is then used to create a model-specific algorithm to solve the specific machine learning problem. Model-based machine learning can be applied to pretty much any problem, and its general-purpose approach means you don’t need to learn a huge number of machine learning algorithms and techniques.



                         The main Challenges Of Machine Learning
                         
Bad Data:
        Insufficient quantity of Data<br/>
        The unreasonable effectiveness of data <br/>
        Non representative training data (Sampling Bial) <br/>
        Poor Quality Data <br/>
        Irrelevant Features: can be solved by <br/>
                Feature Selection <br/>
                Feature Extraction : Combining existing features to produce more useful one.
                Feature Engineering and Gathering new data. <br/>
       Overfitting: CAn be solved by <br/>
               Simplifying the model with fewer parameters, or by reducing the number of attributes or constainig the model. <br/>
               Gather more data <br/>
               Reduce noise by fixing data error and removing outliers. <br/>
       Underfitting: Can be solved by <br/>
               Selecting a more powerful model with more parameter. <br/>
               Feeding better features to the learning algorithm (Feature Engineering|) <br/>
               Reducing the constraints on model.
               
               
               
               
                       Testing and Validating Data
                       
The only way to know how well a model will generalize to new cases is to actually try out new on cases 