## Cheat Sheet

Whenever you're confused about git, come read this cheat sheet. Remember that all git commands can be run with the `--help` option. For example:

`$ git branch --help` or `$git log --help`

### Essential Git Commands

####Create a new git repository
`$ git init` - Create a new, local repository

#### Repo Status
`$ git status` - Check the status of your current repository and see which files have changed.

`$ git diff` - __Fill Me Out__

#### Repo History
`$ git log` - __Fill Me Out__

`$ git log --oneline --decorate --color --graph --all` - __Fill Me Out__

`$ git log -p [filename]` - Shows git log with file contents visible

#### Stage files to commit
`$ git add <filename>` - Add file contents to the index

`$ git add -A` - Adds all files' contents to the index

#### Commit changes in staged files
`$ git commit -m "<commit message>"` - adds staged changes to commited changes

#### Branching
`$ git branch <branch name>` - Creates a new branch

`$ git branch` - List, create, or delete branches.

`$ git checkout <branch name>` - __Fill Me Out__

#### Merging

`$ git merge <branch name>` - __Fill Me Out__
