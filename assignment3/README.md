## Assignment 3: Policy Gradient

**Due Date: Feb 23(Fri), 11:00 PM PST. See course webpage for the late day policy.**

This assignment will provide you with practice with policy gradient. We will use Open AI gym [Mujoco Environment](https://github.com/openai/mujoco-py) for the programming component. You need to sign up for their [license](https://www.roboti.us/license.html).

## Tasks

There are 2 parts to this assignment: written and code components. Both parts are required.

The coding assignment, including some starter code, is available [here](http://web.stanford.edu/class/cs234/assignment3/assignment3.zip).

The written homework questions are available [here](http://web.stanford.edu/class/cs234/assignment3/assignment3.pdf).

## Setup

*Note: Please be sure you have Python 2.7.x installed on your system. The following instructions should work on Mac or Linux. If you have any trouble getting set up, please come to office hours and the TAs will be happy to help.*

**[Optional] virtual environment**: Once you have unzipped the starter code, you might want to create a [virtual environment](https://docs.python-guide.org/en/latest/dev/virtualenvs/) for the project. If you choose not to use a virtual environment, it is up to you to make sure that all dependencies for the code are installed on your machine. To set up a virtual environment, run the following:

```
cd assignment3
sudo pip install virtualenv      # This may already be installed
virtualenv .env                  # Create a virtual environment
source .env/bin/activate         # Activate the virtual environment
pip install -r requirements.txt  # Install dependencies
 # install gym
git clone https://github.com/openai/gym
cd gym
pip install -e . # minimal install
pip install mujoco-py==0.5.7
# Work on the assignment for a while ...
deactivate                       # Exit the virtual environment
```

**Install requirements (without a virtual environment)**: To install the required packages locally without setting up a virtual environment, run the following:

```
cd assignment3
pip install -r requirements.txt  # Install dependencies
 # install gym
git clone https://github.com/openai/gym
cd gym
pip install -e . # minimal install
pip install mujoco-py==0.5.7
```

## Submitting your work

See Piazza for more submission instructions. Remember, you MUST follow the instructions and submit your code and writeup.

Once you are done working, run `make submit` and transfer the zip file to the corn machine. In the corn machine, use `/afs/ir/class/cs234/submit` to submit the coding part.

For the written component, please upload a PDF file of your solutions to Gradescope. When asked to map question parts to your PDF, please map the parts accordingly as courtesy to your TAs. This is crucial so that we can provide accurate feedback. If a question has no written component (completely programmatic), map it on the same page as the previous section or next section.