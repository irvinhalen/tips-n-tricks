# 🍆 Tips & Tricks 🎃

> This one is for 🐍 *Python*


## Getting Started

### Environment with 🐍 Anaconda

- Create environment
    - -n flag stands for name
    - you can specify the version of Python
```sh
conda create -n environment_name python=3.11.7 anaconda
```
- Activate environment
```sh
conda activate environment_name
```
- Deactivate environment
```sh
conda deactivate
```
- Export environment
    - | grep -v "^prefix: " excludes the prefix line from the yaml file
        - | stands for pipe
        - -v stands for invert
        - \> stands for redirecting output
```sh
conda env export | grep -v "^prefix: " > environment_name.yml
```
- Create environment from yaml file
```sh
conda env create -f environment_name.yml
```

### New Project

1. Create a file with the extension .py for example: ```Project.py```
2. Run the code
```sh
python Project.py
```

### Requirements

- Install the requirements from a text file
    - -r flag stands for requirement
    - requirements.txt is the name of the text file
```sh
pip install -r requirements.txt
```

- Listing the requirements from your app to a text file
```sh
pip freeze > requirements.txt
```
