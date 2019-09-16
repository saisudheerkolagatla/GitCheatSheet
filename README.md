###Git Cheat Sheet###

This cheat sheet summarizes commonly used Git command line instructions for quick reference.

CONFIGURE TOOLING
Configure user information for all local repositories

$ git config --global user.name "[name]" -- Sets the name you want attached to your commit transactions

$ git config --global user.email "[email address]" -- Sets the email you want attached to your commit transactions

$ git config --global color.ui auto -- Enables helpful colorization of command line output

CREATE REPOSITORIES
Start a new repository or obtain one from an existing URL

$ git init [project-name] -- Creates a new local repository with the specified name

$ git clone [url] -- Downloads a project and its entire version history

MAKE CHANGES
Review edits and craft a commit transaction

$ git status -- Lists all new or modified files to be committed

$ git add [file] -- Snapshots the file in preparation for versioning

$ git reset [file] -- Unstages the file, but preserve its contents

$ git diff -- Shows file differences not yet staged

$ git diff --staged --> Shows file differences between staging and the last file version

$ git commit -m "[descriptive message]" -- Records file snapshots permanently in version history
