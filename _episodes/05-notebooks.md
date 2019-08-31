---
title: "Notebooks"
teaching: 60
exercises: 30
questions:
- "What is the difference between applications and notebooks?"
- "How can I use a notebook in my own research?"
- "How can I work with applications through a notebook?"
- "What are the current e-infrastructure options in running a notebook?"
objectives:
- "Understand the advantages and disadvantages of using notebooks."
- "Be able to list the most relevant options for running a notebook, beyond a local installation."
- "Understand how to use existing applications through a notebook."
- "Be able to run a sample notebook through the CyVerse e-infrastructure."
keypoints:
- "First key point. Brief Answer to questions. (FIXME)"
---

> Participants will cover the use of Docker to manage applications to deploy applications and use Jupyter notebooks to interface with applications.

## What are notebooks?

[Literate programming](https://en.wikipedia.org/wiki/Literate_programming) is the basic idea behind dynamic documents and was proposed by Donald Knuth in 1984.  Originally, it was for mixing the source code and documentation of software development together.  Today, we will create dynamic documents in which program or analysis code is run to produce output (e.g. tables, plots, models, etc) and then are explained through narrative writing.

The 3 steps of **Literate Programming**:  

1. **Parse** the source document and separate code from narratives.  
2. **Execute** source code and return results.  
3. **Mix** results from the source code with the original narratives.  

So that leaves us, the writers, with 2 steps which includes writing:  

1. Analysis code  
2. A narrative to explain the results from the analysis code.  

## So, what **is** a Jupyter notebook?

In this case, "_notebook_" or "_notebook documents_" denote documents that contain both code and rich text elements, such as figures, links, equations, etc. Because of the mix of code and text elements, these documents are the ideal place to bring together an analysis description and its results as well as they can be executed perform the data analysis in real time. These documents are produced by the [Jupyter Notebook App](http://jupyter.org/).

As a fun note, "Jupyter" is a loose acronym meaning [Julia](julialang.org), [Python](https://www.python.org/), and [R](https://www.r-project.org/). These programming languages were the first target languages of the Jupyter application, but nowadays, the notebook technology also supports [many other languages](http://github.com/ipython/ipython/wiki/IPython-kernels-for-other-languages).

The main components of the whole Jupyter environment are, on one hand, the notebooks themselves and the application. On the other hand, you also have a notebook kernel (that is the language interpreter that will be executing the code in the background) and a notebook dashboard.

And there you have it: the Jupyter Notebook - there are also several [examples of Jupyter notebooks](https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks) that you can see/browse.



{% include links.md %}
