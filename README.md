# Practical Software Management

## Initial Lesson Development

**Episode Responsibilities**

|Episode|Lead|Authors|Description|Hands-on/Discussion only|Approximate time|
|-------|----|-------|-----------|------------------------|----------------|
|01 - Workshop Overview|Jason|Jason|Brief overview of CyVerse (publicly funded infrastructure project) and how it is being adopted internationality (CyVerse UK/Austria/Australia), how you can make free use of it, and how these and other technologies are relevant to European bioinformatics and infrastructure projects (e.g. ELIXIR and EOSC). We will also introduce common tools and related vocabulary for computing in life science research.|Discussion|00:30|
|02 - 4OSS Principles|Mateusz|Mateusz, Fotis Allegra|Participants will learn about the 4OSS principles and how they support reproducible, high-impact science through sustainable software and computing choices.|Hands-on|00:30|
|03 - GitHub|Mateusz|Mateusz, Fotis, Allegra|Participants will get a brief introduction to repository creation in Github and learn the value of developing code that is open from day one. Introduction of licensing and recommendations for fostering and managing contributions.|Hands-on|01:45|
|04 - Containers||Jason, Rob?|Participants will be introduced to Docker as a solution for software reproducibility, portability, and management. We will cover the basics of Docker and describe the process of pulling and running containers, including from popular repositories such as docker hub and biocontainers.|Hands-on|01:00|
|05 - Notebooks|Fotis|Fotis, Mateusz|Participants will cover the use of Docker to manage applications to deploy applications and use Jupyter notebooks to interface with applications.|Hands-on|01:30|
|06 - Application deployment |Jason|Jason, Rob?|Participants will take applications developed in the workshop and see how they can be deployed as usable applications in CyVerse as well as My Binder.|Hands-on|02:15|
|07 - Roadmapping and summary ||Rob?|Participants will work in small teams to develop learning roadmaps to be implemented post-workshop (How will the workshop change what they are now doing? What questions do they still have? What technologies would the like more information on? etc.). These will be shared and collected and the instructional team will leave additional feedback and suggestions on the maps during and shortly after the workshop.|Discussion|01:00|

**Episode Descriptions**

Here is a space with brief notes for each episode. The purpose is to share enough
detail here that subsequent/episodes can be aligned.

When you are ready post your learning objectives here. Also pay attention to
the dependencies  (i.e. things you need a previous episode to accomplish);
indicate all dependencies you need (they may not be from the immediately previous
episode). Also indicate any products you create that you think will be used downstream.
Also - if users will need to install software, import data, sign-up for
an account, please note that here so we have an easier time building the
workshop setup info.


----

### Workshop Overview

**Draft learning objectives**:

 - Understand the objectives for the workshop
 - Understand the background and purpose of the CyVerse project
 - List current European iniatives concerned with the promotion of
   software reproducibility/sustainability in the life sciences

**Narrative**:

This short overview will set the tone for the workshop. Learners should
understand what our goals are, but realize that the materials are
work-in-progress (and that we can be flexible). Learners should also know
what are some European projects they might want to learn more about.

**Dependencies from previous episode**:

None

**Products/outputs for subsequent episodes**:

 - Product/output:
   - Learners should confirm at this stage they have completed pre-workshop
     setup items, and be invited to alert instructors to unresolved problems.

**User setup notes**:

 - Tool/dataset/account: CyVerse Account

----

### 4OSS Principles

**Draft learning objectives**:

**Narrative**:

**Dependencies from previous episode**:

 - Episode:
 - Dependency:

**Products/outputs for subsequent episodes**:

 - Product/output:

**User setup notes**:

 - Tool/dataset/account:
 - Tool/dataset/account:

----

### GitHub

**Draft learning objectives**:

**Narrative**:

**Dependencies from previous episode**:

 - Episode:
 - Dependency:

**Products/outputs for subsequent episodes**:

 - Product/output:

**User setup notes**:

 - Tool/dataset/account:
 - Tool/dataset/account:

----

### Containers

**Draft learning objectives**:

- Understand what containers are
- List some of the benefits of using Docker ontainers
- Be able to search for and pull a Docker container or Biocontainer
- Be able to start and interact with a Docker container
- Understand how Dockerfiles are used to create containers


**Narrative**:

We will introduce Docker containers and through a series of hands-on exercises
we will guide users through basic container functions.

**Dependencies from previous episode**:

 - Episode: 03 GitHub
 - Dependency: Learners may need to be able to navigate github to examine
   Dockerfiles.

**Products/outputs for subsequent episodes**:

 - Product/output: Learners will pull a container that allows them to run
   a Jupyter notebook
 - Product/output: Learners can pull containers for subsequent episodes

**User setup notes**:

 - Tool/dataset/account: CyVerse account
 - Tool/dataset/account: Dockerhub account
 - Tool/dataset/account: GitHub account

----

### Notebooks

**Draft learning objectives**:

**Narrative**:

**Dependencies from previous episode**:

 - Episode:
 - Dependency:

**Products/outputs for subsequent episodes**:

 - Product/output:

**User setup notes**:

 - Tool/dataset/account:
 - Tool/dataset/account:

----

### Application deployment

**Draft learning objectives**:

- Understand how MyBinder and CyVerse can host notebooks and containers
- Be able to generate a MyBinder notebook from a GitHub repository
- Be able to deploy a container through CyVerse

**Narrative**:

Using a single GitHub repository with a sample Notebook and dependencies, we
will guide users through deploying this application on MyBinder and on CyVerse
VICE.

**Dependencies from previous episode**:

 - Episode: 05 Notebooks
 - Dependency: Jupyer notebook and dependencies for deployment

**Products/outputs for subsequent episodes**:

 - Product/output: A notebook with the tools for a reproducible analysis

**User setup notes**:

 - Tool/dataset/account: CyVerse account
 - Tool/dataset/account: Dockerhub account
 - Tool/dataset/account: GitHub account

----

### Roadmapping and summary

**Draft learning objectives**:

**Narrative**:

**Dependencies from previous episode**:

 - Episode:
 - Dependency:

**Products/outputs for subsequent episodes**:

 - Product/output:

**User setup notes**:

 - Tool/dataset/account:
 - Tool/dataset/account:

----

## ALL ITEMS BELOW TBD

## Contributing

We welcome all contributions to improve the lesson! Maintainers will do their best to help you if you have any
questions, concerns, or experience any difficulties along the way.

We'd like to ask you to familiarize yourself with our [Contribution Guide](CONTRIBUTING.md) and have a look at
the [more detailed guidelines][lesson-example] on proper formatting, ways to render the lesson locally, and even
how to write new episodes.

Please see the current list of [issues][FIXME] for ideas for contributing to this
repository. For making your contribution, we use the GitHub flow, which is
nicely explained in the chapter [Contributing to a Project](http://git-scm.com/book/en/v2/GitHub-Contributing-to-a-Project) in Pro Git
by Scott Chacon.
Look for the tag ![good_first_issue](https://img.shields.io/badge/-good%20first%20issue-gold.svg). This indicates that the mantainers will welcome a pull request fixing this issue.


## Maintainer(s)

Current maintainers of this lesson are

* FIXME
* FIXME
* FIXME


## Authors

A list of contributors to the lesson can be found in [AUTHORS](AUTHORS)

## Citation

To cite this lesson, please consult with [CITATION](CITATION)

[lesson-example]: https://carpentries.github.io/lesson-example
