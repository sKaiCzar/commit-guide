# commit-guide

The following guides explain my git commit process. 

## Commit Style

Prefered commit style for my projects
`commit_string = "[ <commit_type> ] : <commit_message>"`.
Commit_type can be be an array too to better explain a commit, but it is preferred that there is a single instance of commit_type in a commit.

### Types of commit:

The following should be the types of commit:

- setup : barebone setting up default project
- config : adding config files
- migration : migration of tech stack
- feature : adding new feature
- fix : bug fix
- patch : resolving hacks 
- refactor : refactoring and or inclusion of new design pattern
- docs : documentation
- style : style update
- cleanup : removing obsolete code or feature
- perf (performance improvement) 
- test : changes that affect test or test system
- build : changes that affect build system
- ci : continuous integration
- chore : non core logic commits 
- revert : back tracking to old commit
- update : errata

### Commit messages:

The commit message should:

- be clear
- be under 32 characters (personal preference)
- not be a sentence
- explain the commit
- be in english language. (preferably american eng because it has smaller char length for same words).

## Atomic Commit
For productivity reasons prefer atomic commits, i.e, commits of smallest meaningful change. Meaningful is ofcourse a subjective term but a general explaination for atomic commit can be changes containing all the essential elements to stand on its own. Smaller tweaks, like fixing tiny bugs or adding types which are necessary parts of the whole, but on their own, they don’t bring explicit value to the feature.

## Squashing commits
You can squash commits to a meaningful commit after a sufficienty large period or a development cycle has been completed and scope of previous change has little to no aftermath at the current stage.

Notes:
- Prefer git rebase in interactive mode over git pull unless there is an use case for any other command.
- Prefer `git add --interactive` over `git add .` .
