# Git in Python

A command line interface having similar functionality to Git written in Python.
Minimal usage of external libraries.
- Support for GitHub as external server
## Installation 

Make sure you have Git & Python3 installed on your local.

## Run Locally

Clone the project

```bash
  git clone https://github.com/tripathyprateek/git-in-python
```

Go to the project directory

```bash
  cd git-in-python
```


  
## Usage
Initialise an empty folder

```
python3 main.py init [folder_name]
cd [folder_name]
```
Next add new files to the folder and check for changed files
```
python3 main.py status
python3 main.py add main.py
```
Commiting the files
```
python3 main.py commit -m "Initial Commit"
```
Pushing the files to Remote Server(GitHub in our case)
```
python3 main.py push "[REPOSITORY_URL]"
```
