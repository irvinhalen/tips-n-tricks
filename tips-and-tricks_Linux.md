# 🍆 Tips & Tricks 🎃

> This one is for 🐧 *Linux*


## Getting Started

### Running on 🪟 Windows

1. Run command
```sh
wsl
```

### Creating a Symbolic Link

1. Run command
```sh
ln -s /mnt/C/Users/Test\ Tickles/ ~/winhome
```


## Frequently Used Commands

### Copy

### Move

### ZIP

- Archive
    1. Open a terminal
    2. Navigate to the parent of the root folder of the project
    3. Run the command to zip
        ```
        zip -r project_name.zip project_name -x project_name/frontend/node_modules/\* -x project_name/backend/vendor/\*
        ```
        - *project_name.zip* is the name of the output
        - *project_name* is the name of the input
        - -r flag stands for recursive
        - -x flag stands for exclude
- Extract
    1. Open a terminal
    2. Run the command to unzip
        ```
        unzip project_name.zip -d destination_folder
        ```
        - -d flag stands for destination
