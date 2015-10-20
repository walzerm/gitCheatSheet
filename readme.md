## Cheat Sheet

Whenever you're confused about git, come read this cheat sheet. Remember that all git commands can be run with the `--help` option. For example:

`$ git branch --help` or `$git log --help`

### Essential Git Commands

####Create a new git repository
`$ git init` - Create a new, local repository

#### Repo Status
`$ git status` - Check the status of your current repository and see which files have changed.

`$ git diff` - it compares two files and outputs the difference between them

#### Repo History
`$ git log` - it displays the logs of your commits with each commit ID, auther, date and message.
`$ git log --oneline --decorate --color --graph --all` - it displays the logs of your previous commits with color decorations and in one line only.

`$ git log -p [filename]` __Fill Me Out__

#### Stage files to commit
`$ git add <filename>` - __Fill Me Out__

`$ git add -A` - __Fill Me Out__

#### Commit changes in staged files
`$ git commit -m "<commit message>"` - __Fill Me Out__

#### Branching
`$ git branch <branch name>` - Creates a new local branch.

`$ git branch` - Shows the branches.

`$ git checkout <branch name>` - Switches to this branch.

#### Merging

`$ git merge <branch name>` - Merges this branch with the master