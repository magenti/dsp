# Install software on your computer


### Install [git](http://git-scm.com/).

You have it installed if you can run `git --version` at the command
line and get output like `git version 2.3.5`.


### Install [Anaconda](http://continuum.io/downloads).

There are two things you can verify to check your install.

First, from the command line, all of the following should start up
some kind of Python interpreter:

```bash
python
ipython
ipython notebook
spyder
```

Second, inside any of those Python interpreters, you should be able to
do all of these without error:

```python
import numpy
import scipy
import matplotlib
import pandas
import statsmodels
import sklearn
```

### Install [Homebrew](http://brew.sh/) on Mac

If you use a Mac, install Homebrew if you don't
have it yet. You could use Homebrew to manage your `git` and `python`
installs as well, but the methods given above are very good and more
cross-platform.

---

Did you install Python 2 or 3? Why?  

>> My understanding is that both releases have own advantages but as a newbie in Python maybe version 2 is a better choice than version 3 to start with. 
While python 3 is the future of this programming language, some older libraries and packages may only be working in Python 2.
In addition, all books I am reading on Machine Learning have codes written in Python 2. To ensure reproducibility, I preferred to install version 2.7  

###Q2. Which Python Version Installed   

How can you check the version of Python installed if you happen to be on an unfamiliar computer?

>>  There are several way to check which Python version is installed on a computer depending on if python is already running or not:

>> 1)	from the command line you can run:
```
python --version
```

>> 2)	when you run python or iPython, the very first line in the header specifies which version of python is running. 
in my case:  

>> Python 2.7.11|Anaconda 2.5.0 (x86_64)| (default, Dec  6 2015, 18:57:58) 

>> 3)	If python is running, you can run the following:
```
import platform
platform.python_version()
```
or 
```
import sys
sys.version
```
 


