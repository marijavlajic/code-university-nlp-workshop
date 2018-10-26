***CODE University - Intro to Natural Language Processing Workshop***

Even though it isn’t what immediately springs to mind when we think about data, a large chunk of information available to us comes in the form of unstructured text — think Wikipedia or news articles, health records, online reviews, emails, even tweets. Natural Language Processing (NLP) provides techniques for turning this unstructured input into format machines can understand, analyse, and interpret.

In this workshop I will:
* introduce basic concepts that help us turn text into structured data like text preprocessing and feature extraction, 
* showcase the tools available for tackling NLP tasks, 
* teach you how to apply what you’ve learned to some of the real-world NLP tasks such as machine translation, sentiment analysis, and topic modelling. 

---

### Getting set up

#### Installing and Configuring Python
* You will need Python 3.* installed on your computer. Go to [the Python website](https://www.python.org/downloads) and find the right download for your OS.

#### Downloading Anaconda
* Anaconda is a python distribution which includes pretty much everything you need for out-of-the-box data science work.
* Download and install Anaconda (for a Python 3.* version) from [https://www.anaconda.com/download](https://www.anaconda.com/download)

#### Getting the Extra Libraries
* There are a few extra packages you'll need for this workshop. Run the lines below to get everything set up:

```
conda create -n nlp-workshop python pandas nltk numpy scikit-learn scipy matplotlib seaborn ipython jupyter

conda activate nlp-workshop
```

#### Downloading the code
You can download the repository zip file or clone the repository.

#### Downloading the movie review dataset
Download the IMDB movie review dataset [here](http://ai.stanford.edu/~amaas/data/sentiment/).

#### Running the notebooks
* Run the following from the project's root folder:
`jupyter notebook`
* Then, open the `Working with text in Python & NLTK` notebook.
