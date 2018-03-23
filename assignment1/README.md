## Assignment 1: Starting to Reinforcement Learn

**Due Date: 1/24 (Wed) 11:00 PM PST. See course webpage for the late day policy.**

This assignment will provide you with practice with fundamental ideas in sequential decision making and the start of reinforcement learning. We will use Open AI gym for the programming component.

## Tasks

There are 2 parts to this assignment: written and code components. Both parts are required.

The coding assignment, including some starter code, is available [here](http://web.stanford.edu/class/cs234/assignment1/assignment1.zip).

The written homework questions are available [here](http://web.stanford.edu/class/cs234/assignment1/assignment1.pdf).

## Setup

*Note: Please be sure you have Python 2.7.x installed on your system. The following instructions should work on Mac or Linux. If you have any trouble getting set up, please come to office hours and the TAs will be happy to help.*

**[Optional] virtual environment**: Once you have unzipped the starter code, you might want to create a [virtual environment](http://docs.python-guide.org/en/latest/dev/virtualenvs/) for the project. If you choose not to use a virtual environment, it is up to you to make sure that all dependencies for the code are installed on your machine. To set up a virtual environment, run the following:

```
cd assignment1
sudo pip install virtualenv      # This may already be installed
virtualenv .env                  # Create a virtual environment
source .env/bin/activate         # Activate the virtual environment
pip install -r requirements.txt  # Install dependencies
 # install gym
git clone https://github.com/openai/gym
cd gym
pip install -e . # minimal install
# Work on the assignment for a while ...
deactivate                       # Exit the virtual environment
```

**Install requirements (without a virtual environment)**: To install the required packages locally without setting up a virtual environment, run the following:

```
cd assignment1
pip install -r requirements.txt  # Install dependencies
 # install gym
git clone https://github.com/openai/gym
cd gym
pip install -e . # minimal install
```

## Submitting your work

Submit both your written assignment and coding assignment by following the 

**Submission Instructions**

.