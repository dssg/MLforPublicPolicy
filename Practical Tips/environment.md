# Setting up your work environment
We're gonig to assume you're using some type of linux environment, and that you're conecting to a remote server from your local machine.

Some tips you'll find useful:
* **SSH keys**: Set up an ssh key to log in. This will allow you to log in using a key instead of a password
* **virtualenv**: When starting a new python project, it's a good idea to set up a python virtual environment. This allows  you to keep all the dependencies 
for that project in one place and isolate one project from another in case there are clashes with version numbers of modules. it also allows you to then create a requirements.txt
file that someone else can run to recreate the environment and run your code. You can create a new environment by 
running "_virtualenv nameofproject_". To go to in the environment and start working, you can run "_source nameofproject/bin/activate_". You can find more details [here](https://realpython.com/blog/python/python-virtual-environments-a-primer/)
* **screen** or **tmux**: When you start working on a remote server, it's much nicer to first start a tmux or screen session to start long processes so you don't have to wait around for them to
finish before going outside for a nap on the beach. tmux or screen sessions persist, your process continues even when you close 
the window you logged in with from your local machine. you can also have different tmux or screen sessions for different projects you're working on.
* **Running Jupyter notebooks remotely**: You can run a jupyter notebook on a remote server and connect to it from your local browser by using an ssh tunnel. See [link](https://yangcha.github.io/Jupyter-Notebook/) for more details.


