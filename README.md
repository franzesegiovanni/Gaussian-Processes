# Gaussian Processes - From Start to Hero
## Preliminarities 
1. What is Uncertainty? https://en.wikipedia.org/wiki/Uncertainty_quantification?oldformat=true

## Books and Book Chapters
1.  **Gaussian Processes for Machine Learning** by Carl Edward Rasmussen and Christopher K. I. Williams published by The MIT Press. http://www.gaussianprocess.org/gpml/ and [pdf] http://www.gaussianprocess.org/gpml/chapters/RW.pdf.

This is the ultimate referece for Gaussian Processes. The book introduces Gaussian Processes, comprehensively covers regression and classfication with Gaussian processes and describes in detail related topics including covariacne funcions (i.e., kernels), hyperparamters, approximations and much more. I will strongly recommend this book for any one interested in learn about Gaussian Processes and using these in their machine learning work.

2.  **Machine Learning A Probabilistic Perspective (Chapter 15)** by Kevin P. Murphy published by The MIT Press. https://mitpress.mit.edu/books/machine-learning-1 and https://www.cs.ubc.ca/~murphyk/MLbook/.

3. **Pattern Recognition and Machine Learning (Section 6.4)** by Christopher M. Bishop. https://www.springer.com/us/book/9780387310732 and https://www.microsoft.com/en-us/research/people/cmbishop/#!prml-book

4.  **Information Theory, Inference and Learning Algorithms (Chapter 45)** by David J. C. MacKay. Links: Book http://www.inference.org.uk/mackay/itprnn/ps/534.548.pdf.

5.  **Bayesian Reasoning and Machine Learning (Chapter 19)** by David Barber. http://web4.cs.ucl.ac.uk/staff/D.Barber/textbook/091117.pdf.

## Courses and Notes
1.  **CS281: Advanced Machine Learning (Lecture 19)** Links https://www.seas.harvard.edu/courses/cs281/.

2.  **CS229: Machine Learning**. http://cs229.stanford.edu/section/cs229-gaussian_processes.pdf

3. **Gaussian Process Summer School**. https://www.youtube.com/watch?v=tkDYEAoN5Eo&list=PLZ_xn3EIbxZGcqHGFj-P_SI6OCXy8TfoL


## Peer-reviewed and non-peer reviewed resources
1.  **Gaussian Processes: A Quick Introduction** by Mark Ebden. https://arxiv.org/abs/1505.02965
2.  **A Visual Exploration of Gaussian Processes** by Jochen Görtler et al. https://distill.pub/2019/visual-exploration-gaussian-processes/
3.  **Gaussian Processes for Dummies** by Katherine Bailey. http://katbailey.github.io/post/gaussian-processes-for-dummies/
4.  **Gaussian processes** by Martin Krasser. http://krasserm.github.io/2018/03/19/gaussian-processes/
5.  **Fitting Gaussian Process Models in Python** by Chris Fonnesbeck. https://blog.dominodatalab.com/fitting-gaussian-process-models-python/
6.  **How to design the best kernel for your applications?** https://www.cs.toronto.edu/~duvenaud/cookbook/

## How to deal with Big Databases? ##
1. **A Tutorial on Sparse Gaussian Processes and Variational Inference** by Felix Leibfried https://arxiv.org/pdf/2012.13962.pdf
2. **Gaussian Processes for Big Data** by James Hensman et al. https://arxiv.org/ftp/arxiv/papers/1309/1309.6835.pdf
3.  **Distributed Gaussian Process**   by Marc Deisenroth et al. https://arxiv.org/pdf/1502.02843.pdf

# Learning about Gaussian Process approximation: Approximate the prior vs approximate the posterior
1. Understanding and Comparing Scalable Gaussian Process Regression for Big Data: https://arxiv.org/pdf/1811.01159v1.pdf 
This paper is making the distinction between FITC and SVGP on what they are actually approximating. FITC is doing an approximation of the prior distribution while SVGP is doing an approximation of the posterior distribution. 
2. FITC and VFE https://bwengals.github.io/fitc-and-vfe.html. This is an interesting blog post for the comparison of FITC to VFE. From a practical point of view, FITC and SVGP are optimizing one the log marginal likelihood and another the Evidence Lower Bounds however pratically, the two cost functions are really similar and it is interesting. This blogpost highlights this again. 
3. Sparse Variational Gaussian Procees : https://tiao.io/post/sparse-variational-gaussian-processes/
4. Understand the basic of Variational Inference https://zhiyzuo.github.io/VI/ & https://arxiv.org/pdf/1601.00670.pdf
5. The Variational Approximation for Bayesian Inference https://www.cs.uoi.gr/~arly/papers/SPM08.pdf
6. Scalable Variational Gaussian Process Classification https://proceedings.mlr.press/v38/hensman15.pdf
7. Scalable Gaussian process inference using variational methods https://api.repository.cam.ac.uk/server/api/core/bitstreams/c3612b80-36a4-4620-92ce-d389eeea98f8/content

## How to deal with the Curse of Dimensionality, i.e. many inputs?  ##
1. **Convolutional Gaussian Process** by Mark van der Wilk
 https://proceedings.neurips.cc/paper/2017/file/1c54985e4f95b7819ca0357c0cb9a09f-Paper.pdf [https://gpflow.readthedocs.io/en/master/notebooks/advanced/convolutional.html]

## Learn about Deep Gaussian Process
1. **Learn first about Latent Variable Modelling with Gaussian Process**  by Gregory Gundersen. https://gregorygundersen.com/blog/2020/07/14/pca-to-gplvm/
2. **Bayesian Gaussian Process Latent Variable Model** by Neil Lawrence. http://proceedings.mlr.press/v9/titsias10a/titsias10a.pdf
3. **Introduction on Gaussian Process** by Neil Lawrence. http://inverseprobability.com/talks/notes/introduction-to-deep-gps.html
4. **Deep Gaussian Process**. by Andreas C. Damianou, Neil D. Lawrence.  https://arxiv.org/abs/1211.0358

# Gaussian Process for Robotics and Control 
## Gaussian Process for Model Learning and (Predictive) Control ##
1. **PILCO: A Model-Based and Data-Efficient Approach to Policy Search** by Marc Peter Deisenroth et al. https://mlg.eng.cam.ac.uk/pub/pdf/DeiRas11.pdf
2. **Cautious Model Predictive Control using Gaussian Process Regression** by Lukas Hewing https://arxiv.org/pdf/1705.10702.pdf
3. **ILoSA: Interactive Learning of Stiffness and Attractors** by Giovanni Franzese et al. https://arxiv.org/pdf/2103.03099.pdf

# Visualization of Gaussian Process
1. https://infallible-thompson-49de36.netlify.app/
2. http://smlbook.org/GP/
3. http://www.tmpl.fi/gp/
4. https://chi-feng.github.io/gp-demo/


