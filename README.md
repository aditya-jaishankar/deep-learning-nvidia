# deep-learning-nvidia

## Courses

Fill in the syllabus here so I don't forget

* Fundamentals of Deep Learning for Computer Vision
* Fundamentals of Deep Learning for Multiple Datatypes

### Links and Resources:

* Pedro Domingoes book
* ImageNet TED Talk
* [Accuracy, loss function, gradient descent](https://developers.google.com/machine-learning/crash-course/descending-into-ml/training-and-loss)
* [5 minute convolution and CNN presentation](https://youtu.be/YRhxdVk_sIs)
* [Caffe in a day](https://docs.google.com/presentation/d/1HxGdeq8MPktHaPb-rlmYYQ723iWzq9ur6Gjo71YiG0Y/edit#slide=id.gc2fcdcce7_216_0) - Caffe is a python library for paralellization
* [Andrew Ng on Bias Invariance]
* That there are different types of artificial "brains" that are designed to learn different types of things. Learning which architectures have been used to solve problems similar to yours is one of the core skills of successful Deep Learning. In Approach 2, you saw how changing a few constraints could change the behavior of a network. In Approach 3, we'll demonstrate the benefits of research, expertise, and iteration with the caveat that you can use these networks and models without being their designer. The challenge faced by the designers of the network we'll use was what is the most efficient and accurate way to map the input output pairings from out data.
* [Biolerplate NVIDIA code](ngc.nvidia.com)
* Might need a edx course on parallel programming, GPU computation, etc. - [Resource on advantages and disadvantages of GPUs](https://superuser.com/questions/308771/why-are-we-still-using-cpus-instead-of-gpus)

### TensorFlow Notes

* Cardiac image dataset
  - https://smial.sri.utoronto.ca/LV_Challenge/Data.html
  - http://www.midasjournal.org/browse/publication/658
  - http://www.cardiacatlas.org/studies/sunnybrook-cardiac-data/
  - https://www.kaggle.com/c/second-annual-data-science-bowl
* The basic idea is that you have *tensors* that *flow* through a certain set of matrix operations. SO you need to be able to express your problem as a tensor and then define what operations you want to do on your tensors.
* When you build the graph you must specify each so-called Variable (in TensorFlow lexicon). Specifying a piece of data as a Variable tells TensorFlow that it will be a parameter to be "learned", i.e., it is a weight that will be updated as the training proceeds.
* Once the variables and architecture are set up, you set up a session, where you do the computations - the actual flow of tensors through the operations.
* `TensorBoard` API lets you visualize the flow of tensors as a graph. There is other information here and worth exploring
* Deep Learning Specialization seems pretty good (Andrew Ng on Coursera)
