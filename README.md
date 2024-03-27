# gh-actions
### Adding actions from github repo

#### Same Repo

    steps:
        - uses: "./.github/action1"

#### Diffrent Repo
  

    steps:
    	  -uses: "user/repo@ref"

#### Diffrent repo diffrent branch

    steps:
    	-uses: "octocat/my-cool-action@develop"
#### Docker image

    steps:
    	-uses: "docker://python:3.9"
testing auto mere