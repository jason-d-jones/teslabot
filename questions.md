### What is the definition of a serverless application?

Serverless application architecture provides a simpler way to deploy a cloud application. Serverless applications use a bundle of  managed services. Some configuration options are typically provided, however, you are not required to handle all of the typical details, such as provisioning hardware or even turning it on and off..

### What is the definition of model serving and what are the two types?

Model serving is providing a model as a service. The two types of model serving are batch and online. The online method accepts and handles inputs dynamically as they come in, typically from a published endpoint. The batch method processes inputs that have come in and been stored since the last batch inference job was run.


### What are 3 advantages of deploying using Model Serving methods Vs. deploying on GitHub Pages or HuggingFace for free?

Model serving methods provide many advantages when compared to current free offerings:
1. Much greater scalability of hardware and network resources that allow you to serve a much greater number of end-users.
2. Greater control over the underlying hardware. Your performance requirements might require more RAM, a GPU or something else. Free offerings do not offer much, if any control over the hardware.
3. Service level agreements, specifying things such as uptime guarantees.
4. Technical support. 


### What Is Machine Learning Inference? How Does Machine Learning Inference Work? Please walk us through an example?

Machine learning inference is the process of running the model on some input data. This could be as simple as:
1. JSON post request of a numerical feature vector to an AWS Lambda endpoint.
2. FastAPI calls prediction function with feature vector passed in.

Usually, however, it is more complicated. In addition to the use of more complicated models and data pre and post processing there may be more architectrual elements. For example, the input requestion may need to read the model config and grab features from a feature store. There may also be a model store from which the models are loaded and multiple model serving frameworks..



