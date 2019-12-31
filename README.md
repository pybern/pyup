# pyup - A guide to setup Python for data processing and analytics

Python is interpreted language. Which means unlike compiled langauges which generates machine code from source, it is first intepreted (in most cases, Python refers to the canonical release which is CPython) before compiling to machine code. 

## Installing

Select your installer based on your OS and follow the download instructions of choice from an [Anaconda Distribution](https://www.anaconda.com/distribution/)

To test installation, locate your Anaconda Prompt, in Windows 7 and up, you can hit your Windows key and type "Anaconda Prompt" and type `python`. If successful you will be seeing:

    (base) C:\>python
    Python 3.6.7 (default, Feb 28 2019, 07:28:18) [MSC v.1900 64 bit (AMD64)] on win32
    Type "help", "copyright", "credits" or "license" for more information.
    >>>

### Creating your first virtual enviroment

A virtual enviroment is useful to manage your packages and Python versions for future deployment, Anaconda comes with its own and straight forward vistual enviroment which is easy to use, you can read more about [managing enviroments](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html)

For example, we can create a virtual enviroment with the following command
`conda create --name mytest python=3.7 pip`

`conda` invokes the Anaconda program and the `create --name` command creates an enviroment followed by the name `my test`, Python version `python=3.7` and installs the package `pip`.
