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


## Commands

### Copy

- Copy files
```sh
cp filename path/to/destination
```

- Copy directories
```sh
cp -r path/to/source path/to/destination
```

### Move and/or Rename

- Move files
```sh
mv project_file path/to/destination
```

- Move directories
```sh
mv path/to/source path/to/destination
```

- Rename files
```sh
mv old_project_filename new_project_filename
```

### Remove

- Remove files
```sh
rm project_file
```

- Remove directories
    - -r flag stands for recursive
    - -f flag stands for force
```sh
rm -r -f project_folder
```

### ZIP

- Archive
    1. Open a terminal
    2. Navigate to the parent of the root folder of the project
    3. Run the command to zip
        - *project_name.zip* is the name of the output
        - *project_name* is the name of the input
        - -r flag stands for recursive
        - -x flag stands for exclude
```sh
zip -r project_name.zip project_name -x project_name/frontend/node_modules/\* -x project_name/backend/vendor/\*
```
- Extract
    1. Open a terminal
    2. Run the command to unzip
        - -d flag stands for destination
```sh
unzip project_name.zip -d destination_folder
```
