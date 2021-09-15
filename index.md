Exploring Bias through Linguistic Data

![Sociolinguistics](http://all-about-linguistics.group.shef.ac.uk/wp-content/uploads/2016/03/Sociolinguistic-brain.png)

## Project Description
#### The Project:
I have always been interested in linguistics and how training on different linguistic datasets might lead a Neural Network to make more biased predictions. I want to see if Neural Networks that are trained on a diverse linguistic dataset perform better on Standard American English overall compared to other dialects (such as AAE, the language of ESL speakers, or nonstandard dialects overall). 

We would plan on first identifying the Neural Network models that are most standard for Language evaluation. Then, we would figure out what language data we could use to train a few models. I know that We would then conduct multiple experiments on said data and the models to identify where the models are biased and what "form" of English fits the models best. The analysis would be to identify if a sentence is "grammatical" or at least "understandable" to the model given the grammatical framework of that dialect. 

I would be most interested in evaluating if Standard American English sentences are more "correct" than non-standard forms even if the models are trained on a dataset that represents both. 

### The Software:

As of yet, I don't really know too much about the Neural Networks or the language data that would be best for this project. I know that the constraints for the Neural Networks would be that they can be used for language analysis (train on text and then feed in a new sentence to see if it is "correct/understandable"). For the language data, the only constraint is that we find a dataset that is representative of multiple dialects and not just the standard form. I am aware of one dataset from UMass where they collected 500 tweets and annotated them. Of these tweets, 250 were identified to be part of AAE, so the dataset represents both AAE features and SAE features.

### Goals
* We first figure out what Neural Network models can be used for language analysis
* We then find a dataset that has standard and non-standard English sentences and labels indicating which category a sentence fits in
* We train multiple Neural Networks on a dataset that represents both standard and nonstandard forms of English
* We can test the model after training to see if there is a bias towards evaluating certain sentences are "more correct/understandable" than others depending on what form of English they are from
* If there is a bias, we can use current research to understand why this might be... ie. is the Neural Network pretrained? Is there something about language analysis and processing that might explain this
* If there is not a bias, we can also use current research to support the feasibility of training on a representative dataset and increase visibility for nonstandard forms of English

