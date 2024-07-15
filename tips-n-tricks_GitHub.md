# 🍆 Tips 'n' Tricks 🎃

This one is for 🐈‍⬛ *GitHub*


## Getting Started

### New GitHub Repository

- Web
    1. Click on Repositories tab
    2. Click on New

- Local
1. Create a project
2. Navigate to the root folder
3. Run the command
```sh
git init
git add .
git commit -m 'first commit'
git branch -M main
git remote add origin https://github.com/username/example-project.git
git push -u origin main
```

### Synchronization

- Push
```sh
git push -u origin main
```

- Pull
```sh
git pull
```

### Configuration

- Username
    - remove `--global` flag if you want to configure username on a local repository
    - replace `<username>` with the username of your choice
```sh
git config --global user.name "<username>"
```

- Username Confirmation
    - remove `--global` flag if you want to view the configured username of a local repository
```sh
git config --global user.name
```

- Email
    - remove `--global` flag if you want to configure email on a local repository
    - replace `<email>` with the email of your choice
```sh
git config --global user.email "<email>"
```

- Email Confirmation
    - remove `--global` flag if you want to view the configured email of a local repository
```sh
git config --global user.email
```
