# pyup - A guide to setup Python for data processing and analytics

## Understanding Python a bit more

Python is interpreted language. Which means unlike compiled langauges which generates machine code from source, it is first intepreted (in most cases, Python refers to the canonical release which is CPython) before compiling to machine code. 

## Installing

Select your installer based on your OS and follow the download instructions from https://www.anaconda.com/distribution/

To install simply download the compatitble installer from the provided link. Please note that support for Python 2.x will end in 2020 and the community has started to move forward with Python 3.x. In most cases, the latest installer provided in the link (at time of writing Python 3.7) will suffice.

**Note: during installation, a few key steps to take note of would be the NOT to add Python to your system path enviromental variables and install for the current user only, unless ofcourse you are aware of the results**

To test installation, locate your Anaconda Prompt, in Windows 7 and up, you can hit your Windows key and type "Anaconda Prompt" and type `python`. If successful you will be seeing:

    (base) C:\>python
    Python 3.6.7 (default, Feb 28 2019, 07:28:18) [MSC v.1900 64 bit (AMD64)] on win32
    Type "help", "copyright", "credits" or "license" for more information.
    >>>

### Creating your first virtual enviroment

A virtual enviroment is useful to manage your packages and Python versions for future deployment, Anaconda comes with its own and straight forward vistual enviroment which is easy to use, you can read more about [managing enviroments](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html)





