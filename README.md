# Githooks

## commit-msg
Validate commit message against Conventional Commits specification.

## Set up
Copy hooks to your project's '.git/hooks' directory.

## Global hooks
Create a template directory on your machine.
Within this template directory, create a 'hooks' directory.
For example: mkdir -p ~/.git/templates/hooks
Copy hook files to the 'hooks' directory.
Tell git where to find your templates.
For example: git config --global init.templatedir '~/.git/templates' 

