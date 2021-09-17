# <p align="center"> GIT HELPER </p>

## Below are some of the commands useful

## Global Config and setup

### My favourite doit
```sh
git config --global alias.doit '!git add -A && git commit'
```

### Other global settings

```sh
git config --global user.email "<Email id>"
git config --global user.name "<Name>"

git config  --global core.editor "vim"

git config --global diff.tool kompare
```

###  Remembering githuB  password

```sh
git config --global credential.helper 'cache --timeout=7200'
```

## About Remote Branch

### Checkout remote branch

```sh
git checkout -b <branch name> <remote branch name like origin/someremote>
```

### Cloning Remote branch

```sh
git clone -b <BRANCH_NAME>  <GIT_REMOTE_URL>
```

### Add remote branch

```sh
git push -u origin <branch-name>
```

## Submodules

### Adding submodules

```sh
git submodule add <git repo uri> <submodule name>
```

### Update all submodules recursiveley

```sh
git submodule update --init --recursive
```


