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

`$ git log -p [filename]` Logs what happens in between commits

#### Stage files to commit
`$ git add <filename>` - Stages the file to be added to the repository

`$ git add -A` - Stages the current directory to be added to the repository

#### Commit changes in staged files
`$ git commit -m "<commit message>"` - Adds the staged file to the repository with a message describing the changes

#### Branching
`$ git branch <branch name>` - Creates a new local branch.

`$ git branch` - Shows the branches.

`$ git checkout <branch name>` - Switches to this branch.

#### Merging

`$ git merge <branch name>` - Merges this branch with the master