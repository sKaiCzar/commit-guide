# commit-guide

Prefered commit style for my projects
`commit_string = "[ <commit_type> ] : <commit_message>"`

## Types of commit:

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

## Commit messages:

The commit message should:

- be clear
- be under 32 characters (personal preference)
- not be a sentence
- explain the commit
- be in english language. (preferably american eng because it has smaller char length for same words).

Notes:
- Prefer git rebase in interactive mode over git pull unless there is an use case for any other command.
- Prefer `git add --interactive` over `git add .` .
