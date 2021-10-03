## Welcome to my personal web page

I am a Data science engineer and machine learning master level research student at [**ENS Paris-Saclay**](https://ens-paris-saclay.fr/). I graduated recently from [**École Centrale de Lille**](https://centralelille.fr/) as a data scientist. I am poursuing a master of research in machine learning known in France to be the ***"MVA : Mathématiques, Vision, Apprentissage"***, or in english ***"Mathematics, Computer Vision, and Machine Learning"***. Please find [here](https://www.master-mva.com/) the programm.



### Experience

> **Fundamental Machine Learning**

***`Early stopping for deep learning`***

I worked for 8 months at Inria Lille on a part time internship, on a theritical machine learning subject, which is the problem of `Early Stopping`.
Early stopping refers the time in which one should interupt iterative algorithms such as gradient descent, stochastic gradient descent or its variants (as the momentum, Nestorov, Adam, ... etc), so that we can guarantee at the same time good fit to the data, and keep high generalization capabilities (Bias-Variance dilemma !). The phenomenon of early stopping acts therfore as an *algorithmic* regularization. In neural networks, the problems of local minimums, are often encountred in practice, and there are high chances to stuck in a one as the process progresses. Untill now oracle like stopping rules are widely used in practice. However, for such rules, there are no mathematical guarantess for stopping at the *right time* as the loss landscape is not convex in general. This is perhaps why in almost all deep learning framworks as tensorflow, keras, pytorch, you have to set a patience parameter before to stop. The research about this topic is still ongoing. You can see this [presentation](https://mohammed-hssein.github.io/presentation.pdf) for a short introduction. 

---

> **Applied Machine Learning**

I have worked on many applied deep learning problems : 

***`Itinerary search optimization`*** 

Flight search is a complex process. All starts with a request *(Origin --> Destination)* pair at a specific date. This step triggers a *geographical routes exploration* process, where we explore all the possible paths between the origin and the destination which triggers after the process of linking the routes with the airline carriers, and at the end checking the availability and the pricing to form what we call a travel solution. However, the route exploration process is quite complex. Indeed, we can show that the number of requests can reach billions for each pair, making the suggested possibilities hard to price in real time. The idea was to create an algorithm to rank the routes, and suggest only those that will lead to potential cheapest travel solutions at the pricing server. The machine learning model is an innovative complex deep learning model. For reasons of confidentiality, we can only describe some themes we have been inspiring from : ***Sequence embeddings, attributed embeddings, Residual nets, ...etc***

***`Grassmanian deep learning`***

Manifold learning has become more and more a point of interest in machine learning, ans especially in computer vision. Indeed, gesture recognition, Skeleton recognition, ... and many problems are learning problems where the data relies on a mathematical manifolds as for instance Grasmann manifold, SDP manifold, Orthonormal manifold, ...etc. Convolutional neural networks have been doing great jos in recognition problems, or even in generative modeling, however, sur such manifolds, the architecture has many limitations. The work of this internship, was to adabt, and improve a neural network designed for learning on Grassmannian manifolds. The idea consists on chaging the convolutions with other mathematical transformations and decompositions as the SVD, RU, ...etc. check the report [here](https://mohammed-hssein.github.io/internship-manifold.pdf) and the code [here](https://github.com/Mohammed-Hssein/GrNet).


***`Miscellaneous`***

Deep learning architectures as **Restricted Boltzmann Machines** and **Inception**. More details about the code in my Github repositories.

---

### Interests


I am interested in **Federated learning**, **Reinforcement learning** and **Generative modeling**.

