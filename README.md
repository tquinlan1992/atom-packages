# atom-packages

## Setup
Copy this repository to your `./atom` directory

Recommended way to copy repository to your `./atom`:
1. `cd <path to ./atom>`
2. `git init`
    - delete .git directory if necessary
3. `git remote add origin https://github.com/tquinlan1992/atom-packages.git`
4. `git fetch`
5. `git checkout master`
    - Remove any current files with `rm <path of file>`
    - run `git checkout master` again after removing files
6. Go through steps for 'To install packages' below to install packages


## Updating and Installing packages

- To update packages.list:
    - run `make packages.list`
    - The `README.md` should be deleted from the list in the packages.list file
- To install packages:
    - run `make install-all-packages`
    - or simply run `make`
