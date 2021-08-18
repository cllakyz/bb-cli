# Bitbucket Rest Cli

Use bitbucket from command line.
With this app you can see pull request, pipelines, branchs etc. from your terminal.


# Help Command
Help command lists available methods.
`bb help`
```
Available actions:
[
    "pr",
    "pipeline",
    "branch",
    "auth"
]
```

`bb pr help`
```
Available methods:
[
    "list, l",
    "diff, d",
    "commits, c",
    "approve, a",
    "no-approve, na",
    "request-changes, rc",
    "no-request-changes, nrc",
    "decline",
    "merge, m",
    "create"
]
```

# Auth Command

## Save
`bb auth` or `bb auth save` command to save auth info.

## Show
You can see auth info with using show command. `bb auth show`

--- 

# Pr Command

## List
`bb pr list [branch]` list pull request for repository, You may add optional `brach` parameter to see pull request that made for given branch. For example can can use this command to see pull request that destination is dev branch `bb pr list dev`

## Merge 
`bb pr merge <pr-id>` merge pull request


---

# Pipeline Command

## Latest
`bb pipeline latest` gets latest pipeline info(status, state, etc.).


---

# Branch Command

## List
`bb branch list` lists branchs .