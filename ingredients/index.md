---
layout: default
title: DS Cookbook - Ingredients
---
## Human Capital

### Subject Matter Expert / User
If you’re using machine learning to solve a problem, you first need to understand the problem. Talking to an “end user” or subject matter expert is invaluable to gaining understanding of the problem / context. What’s more, even if you build a great machine learning model that makes accurate predictions, it’s useless if the model does not fit cleanly within a user’s existing workflow (who wants another box / computer at their workstation?). Building software that integrates within existing workflows and solves user pain points requires working closely with users.
- UI aspect is a big factor in a successful ML product. The design aspect focuses on how the user interfaces with the machine learning product: How does the user expect to interact with the model? Is the design intuitive? Would someone not familiar with the product be able to navigate through it pretty easily?  How transparent is the model to the user?  How transparent does it need to be?  This requires a whole problem/pain point discovery period, prioritizing those pain points, proposing all possible solutions, and then prioritizing those solutions.  This ensures you’re focusing on the most important thing and will provide the biggest value.

### Business Owner
The problem owner may not be the person that is experiencing problems, but they have responsibility for solving them. For example, you may be building an image detection algorithm to help an intelligence analyst more easily find enemy supply trucks, but it’s the intelligence company commander who is ultimately responsible. This person may have a higher-level view of the workflow beyond just the end user, can challenge/validate your assumptions about the problem, and serve as an advocate within the organization you’re working for.

### Data Scientist
Does data exploration, cleaning (maybe), visualizing, and builds machine learning models. Often they can build models but aren’t often as skilled in deploying that model into existing software or managing systems-level movement of data.
The role of ‘data scientist’ can often mean many things , up to and including a data engineer. Oftentimes, there are different types of data scientists that will overlap in their respective roles and functions. So, at the risk of some oversimplification, there are two general, overlapping, types of data scientists (it is also worth mentioning that many statisticians also fit within this framework, although their approach to data will be markedly different).
- Data Intelligence Analyst. These are your ‘front-facing’ data scientists. Their work is often far more heavily weighted in dealing with stakeholders, relating analysis to business metrics, and data visualization, and less weighted toward model tuning and development and performing rigorous empirical investigations or tests. They are generally good at understanding the business problem, mapping a well-known data science technique to it, to deliver quick insights.
- Machine Learning Engineer.  These are your ‘rear-facing’ data scientists. Their work will be primarily in the range of optimizing models and features to best meet a certain machine learning task. They are generally much more skilled in mathematics and computer programming and are generally good at taking a well-scoped data science problem and delivering an optimal model.

### Data Engineer
Builds and maintains the platforms that bring (1) enough, (2) clean, (3) timely data to the data scientists. Check out Data Engineering Cookbook by Andreas Kretz.

### Software Developer/UX UI Designer
Software developers build and maintain computer, mobile, or web applications. They typically work closely with the UI/UX Designer, who, in this scope,  is responsible for the design of a software application - specifically what the user interacts with.

#### Software Developer:
There are actually many software developers, but for the scope of this cookbook, we will focus on three main developers you will most likely work with: Front-end, Back-end, and Full-stack developers. Here is a great video on the differences between the three. Bottom line, software developers are typically the ones writing the code that facilitates the application based on a design that is provided by the UX/UI designer.

#### UX/UI Designer:
UX (User Experience) and UI (User Interface) Designers are typically focused on the design of the piece of software, with a large emphasis on usability, functionality, and user experience. UI/UX designers should be involved as early as possible in the design process of any application or project, as their input will shape the usability of the product. For software development, designers typically approach software-design problems with a User Centered Design (UCD) approach. This process involves the user’s feedback at every step and is an iterative process.


<br><br><br><br>


## Programming Language

A programming language is what the computer reads in order to do its tasks. Fortunately, in the 2020s, we have plenty of high-level programming languages to our disposal. We don’t need to deal with any 1s and 0s, and we can write code that is easy to read as a human, yet still fast for the computer to process.

### Python
Python is one of the most popular languages for data science and machine learning. Languages like R and Julia are also great, but we are most experienced in Python and know these resources better. We assume you’re proficient in Python, but here are some resources if you’re learning.

**Books**
- [Automate The Boring Stuff with Python](https://automatetheboringstuff.com/#toc) (free + available for purchase)
    - Start from nothing, learn some great data handling tricks

**Udemy courses** (wait until they are < $20)
- [Complete Python Bootcamp from Zero to Hero](https://www.udemy.com/course/complete-python-bootcamp/?LSNPUBID=JVFxdTr9V80&ranEAID=JVFxdTr9V80&ranMID=39197&ranSiteID=JVFxdTr9V80-Xn_zAW37OWEle3RdoedlLA&utm_medium=udemyads&utm_source=aff-campaign) (Udemy) (350k reviews)
- [Python for Data Science and Machine Learning Bootcamp](https://www.udemy.com/course/python-for-data-science-and-machine-learning-bootcamp/learn/lecture/5736886#overview) (Udemy)  (100k reviews)

<br><br>
### Python Libraries
#### NumPy
This is the standard numerical computing library for Python. Before starting any data science Python script, import [NumPy](https://numpy.org/) to get started.

#### Pandas
A powerful library for cleaning and manipulating tabular data (data in tables, like you get from an excel file or CSV) and plotting. See the [getting started guide](https://pandas.pydata.org/docs/getting_started/index.html#getting-started) and [documentation](https://pandas.pydata.org/docs/reference/index.html).

The creator of Pandas, Wes McKinney, has a  [book](http://amzn.to/2vvBijB) and [GitHub repository](https://github.com/wesm/pydata-book) with code. It’s also covered in the Udemy Data Science Bootcamp course listed above.

#### Matplotlib
Math Plotting Library aka matplotlib is the quintessential library for visualizing data in Python. Here’s the [website](https://matplotlib.org/stable/index.html), [tutorials](https://matplotlib.org/stable/tutorials/index.html) for beginner/intermediate/advanced users, and [examples](https://matplotlib.org/stable/gallery/index.html) of common uses.  Pandas plotting functionality is built on top of Matplotlib, so you can call .plot() directly from a DataFrame. Seaborn is another visualization library you may encounter. It’s also built on top of matplotlib so has much of the same functionality, but extends matplotlib in a few areas.

### Scikit-learn/sklearn
Scikit-learn and its family of related scikit tools, like scikit-image, scikit-network, or scikit-learn-extra, provide an immense number and type of tools for all kinds of data science. Powerful, already optimized tools for everything within the Data Science task list can be found in scikit-learn. Examples include supervised learning, clustering, dimensionality reduction, data preprocessing, scoring metrics, and on and on. Generally, most scikit tools are written as objects in Python. This means the general workflow with using a scikit tool consists of instantiating the tool as an object, fitting it to the data with its object methods, and then using the fit object on data for its specified purpose. Given the wide range of tools available and their ease of use, sklearn is often a good starting point for tools for any given data science project.

### Package Managers
A package manager keeps track of all the packages (like those Python libraries above) you have on your computer or virtual environment. It allows you to easily install new packages and update the ones you have.

#### Pip
[Pip](https://pypi.org/project/pip/) is the Python language package manager that pulls packages from the Python Package Index (PyPI). You download packages like this:<br>
`pip install numpy`

#### Conda
[Conda](https://www.anaconda.com/blog/understanding-conda-and-pi) is a language-agnostic package manager that pulls packages from the Anaconda repository. <br>
`conda install numpy`


<br><br><br><br>
## Development Environment

Your development environment is your workplace - it’s where you’ll spend most of your time. There are lots of different ways to develop code, so choose an environment that makes you comfortable.

### Text Editors
A text editor is a simple, streamlined place to write code. That’s it. It can be notepad or something more slick. Many are free, and there are tons to choose from: [Sublime](https://www.sublimetext.com/) is lightweight and wildly popular; [Atom](https://atom.io/) is customizable and links well with Git (and it can be made into an IDE - see below!); [Vim](https://www.vim.org/) is old-school and has great shortcuts to speed up your coding. The list goes on!

If you’re building something fast and easy, just like to keep things simple, or are a confident coder a clean text editor is the way to go.


### IDEs
If you’re building a complex package with lots of dependencies, working with  multiple languages, or developing something to be wrapped into software, an IDE may be what you’re looking for. An integrated development environment (IDE) is not just a code editor (which can be any text editor) but a toolset for debugging, testing, and execution. Here’s an [overview](https://towardsdatascience.com/best-python-ides-and-code-editors-you-must-use-in-2020-2303a53db24) of Python IDEs.

For non-Jupyter IDEs, it’s really up to preference. Atom is a solid choice, but some people love [PyCharm](https://www.jetbrains.com/pycharm/) for all the bells and whistles for debugging and syntax, others prefer [Visual Studio](https://code.visualstudio.com/) code, which has an RStudio feel and some nice debugging features. [Spyder](https://www.spyder-ide.org/) also comes standard with Anaconda package manager. There are also collaborative, browser-based IDEs, such as [Replit](https://replit.com/site/ide), that try to abstract away some of the friction of selecting an IDE. In the world of IDEs, don’t be overwhelmed with the large number of choices. Just start with one and work with it. Don’t switch until you have sufficiently worked with an IDE, no matter what it is. Sometimes it can be a while before you identify why you prefer one or the other. This kind of approach should be applied to almost anything in the computing industry.



### Notebooks
#### Jupyter
Many data scientists use jupyter notebook because of the ease of experimenting and visualizing, though they’re not good for production coding and are prone to getting messy.
[Beginner’s Guide to Installing Jupyter Notebook Using Anaconda](https://medium.com/@neuralnets/beginners-quick-guide-for-handling-issues-launching-jupyter-notebook-for-python-using-anaconda-8be3d57a209b) and [Jupyter tutorial](https://towardsdatascience.com/jupyter-notebook-for-beginners-a-tutorial-f55b57c23ada) both show easy ways to get started with the Anaconda distribution. There may be locations to access Jupyter notebooks or other development environments  on various DoD Networks. Jupyter notebooks are easily run in [Azure ML studio](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-run-jupyter-notebooks) or in [AWS EC2](https://towardsdatascience.com/setting-up-and-using-jupyter-notebooks-on-aws-61a9648db6c5) instances or within the [AWS Sagemaker Service](https://docs.aws.amazon.com/sagemaker/latest/dg/nbi.html)/Deep Learning AMIs.  [Deepnote](https://deepnote.com/) is a free cloud-hosted and team-based Jupyter notebook environment designed for collaborative experimentation.

#### Colab
Don’t want to set up your own development environment? Need access to a GPU, but don’t want to pay for a cloud provider? Google [Colab](https://colab.research.google.com/) solves some of these problems and it’s pretty easy to use. Here’s a [tutorial website](https://www.tutorialspoint.com/google_colab/your_first_colab_notebook.htm) we like.

If you’re looking for a quick environment to test out some ideas while saving the results to come back to later, notebooks are your best bet.

### Terminals
Also called the command line, a computer terminal is a way to interact with the computer directly without the  graphical user interface (e.g. Windows). Think black screen with monospaced green text. You can use them to do all sorts of things (write files, navigate through your computer directories, interact with git), but you can also use them to run programs, including Python scripts.

#### Command Prompt
This is the basic Windows terminal. Search for ‘cmd’, and you’ll find it.

#### PowerShell
Windows created a fancier terminal to replace the base Command Prompt. This is PowerShell.

#### Terminal
This is the Mac terminal. They weren’t very creative with the name.

You could code data science projects  directly in your terminal...but really this should be reserved for  passing direct commands to your computer.

<br><br><br><br>
## Computing and Storage
You’ve got your team, your code, and your dev environment, but where does all the number-crunching happen? Where does the data live? There are a couple options. We’ll start small and go big.

### Local
This is the computer that’s on your desk or in your lap. It’s obviously easy to use, but it probably doesn’t have too much oomph or space.

### On Premise
These are servers that your organization might set up. They’re server stacks in cold rooms. The benefit of “on-prem” is that you have complete control over the server setup and how they’re managed. The drawback is that you’re responsible for server setup and how they’re managed and need to have someone on your team with those skills

### Cloud
What’s the “cloud”? It’s servers that you don’t have to manage because a big cloud provider (think Amazon, Microsoft, Google) manages them. Nowadays, cloud computing is easy to leverage and you can spin up virtual machines, storage, and more with a few mouse clicks, a few minutes, and a credit card rather than needing to purchase your own gear and learn how to do it from scratch.

#### Amazon Web Services
- [How to make an AWS Account](https://aws.amazon.com/premiumsupport/knowledge-center/create-and-activate-aws-account/).
- [Overview of AWS](https://d1.awsstatic.com/whitepapers/aws-overview.pdf) by Amazon
- [Udemy Course](https://www.udemy.com/course/aws-certified-solutions-architect-associate/) by “A Cloud Guru” (wait until price drops  to < $20)

Key services in getting a prototype built:
- Elastic Compute (EC2) Compute resources for development, model training, or application hosting
- S3 (Cloud data storage)
- Sagemaker (Machine learning platform) AWS’s Jupyter Hub. Has AWS pre-built models or you can build your own.
- CodeCommit (AWS Git)
- IAM (team account/access management)

Articles:
- [Deploying a Python Web App on AWS](https://towardsdatascience.com/deploying-a-python-web-app-on-aws-57ed772b2319?source=false---------0) (TowardsDataScience)
- [Setup and use Jupyter (IPython) Notebooks on AWS](https://towardsdatascience.com/setting-up-and-using-jupyter-notebooks-on-aws-61a9648db6c5?source=false---------3) (TDS)
- [Building a data pipeline from scratch on AWS](https://towardsdatascience.com/building-a-data-pipeline-from-scratch-on-aws-35f139420ebc?source=false---------5) (TDS)

#### Certifications
A note on certifications — the military overfocuses on them. Taking a course to get one of these certifications is a license to learn, not an end in itself. If you don’t use the skills, they will atrophy and all your left is a certificate. Also, don’t believe anyone who tells you that getting a single certification will get you a $200,000 salary as a civilian.

# [[[placeholder for AWS certs image]]]


<br><br>
#### Microsoft Azure
Here’s an [overview of Azure Certifications](https://cloudacademy.com/blog/microsoft-azure-certifications-which-is-right-for-you-and-your-team/) from Cloud Academy. Again, certifications are not an end in themself, but just one way of learning “enough to be dangerous” about the cloud resources you’ll need to build/deploy a product that helps your users.

Data must be stored within a storageaccount, within a container, and then finally within a blockblob (one data file per block blob). The containers can then be registered within your Azure ML Studio, where you do project work. Use the datastore feature to link to a container, and the datasets feature to link to a specific file within your datastore/container.

FastAI has a [good setup guide](https://course.fast.ai/start_azure_dsvm). Ignore info about the library/course.

#### Google Cloud Platform
The Fast AI course has a [good setup guide here](https://course.fast.ai/start_gcp). Ignore info about the fastai library or course itself


<br><br><br><br>
## Deployment

What are the tools available for getting your tool or data science analysis to your user (besides powerpoint slides and excel spreadsheets…)

# [[[placeholder for VMs vs Containers image]]]

<br>
### Docker
Docker is a popular container engine that enables rapid, repeatable deployment of software applications without the burden of creating and resourcing multiple VMs.  In many respects a Docker container resembles a VM, but rather than emulating hardware (all the way down to baremetal), a Docker container emulates a subset of the OS kernel particular to your application needs.  In basic terms, this means that you, the developer, can execute a few Docker commands and have an application-specific environment and all relevant libraries ready to go in minimal time.  This process is repeatable multiple times on the same baremetal without compromising performance or risking system underutilization. A lot of bang for your buck.
