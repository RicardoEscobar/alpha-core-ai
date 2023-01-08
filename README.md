# Alpha Core AI

Is an AI powered tool to help programmers do their job.

# Creation of virtual environments

I'm using the `venv` module to create a _virtual environment_ on top of an existing _Python_ installation, known as the virtual environment’s __base__ Python, and may optionally be isolated from the packages in the base environment, so only those explicitly installed in the virtual environment are available.



Creation of virtual environments is done by executing the command `venv`:

```shell
python -m venv venv
```
__Note__: The version of Python used is 3.11.1 and I created an alias for it, so in my case `python` is equal to `python3`. If the command failed, try with:

```shell
python3 -m venv venv
```

A new folder called `venv` will be created, this is where the virtual environment is.

# Activate the virtual environment

To activate the virtual environment you need to change into the repository directory first.

```shell
cd /path/to/alpha-core-ai
```
Depending on what terminal you used to create the environment, you need to use one of these commands:

## On Git Bash
```shell
source venv/Scripts/activate
```

## On PowerShell

```shell
venv/bin/Activate.ps1
```

## On cmd (windows)
```shell
venv\Scripts\activate.bat
```



__Note__: More details on [How venvs work](https://docs.python.org/3/library/venv.html#how-venvs-work)