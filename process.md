# Process
We tend to leverage as most as possible automatic tools to reduce development time and ensure deployment consistent. 

List of tools, but not limit.

- Git
- CI/CD
- Docker (and Docker Compose, Docker Swarm)
- Deployment bash script

## Git
The branching model we decide to use internally is [**Gitflow Workflow**](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow) because this model is very clear and helpful for continuous integration. Recommended tool is [git-flow](https://github.com/nvie/gitflow).

However, for inter [**Forking Workflow**](https://www.atlassian.com/git/tutorials/comparing-workflows/forking-workflow) is better.

### Git rule
- Rebase when pull code from *develop* branch

> git checkout feature_branch
> 
> git pull --rebase origin develop

- Send pull request after finish feature branch
- **develop** branch always use merge (never rebase at all)
- Always create feature branch when start on new feature, using prefix as predefined like _feature/add\_login\_page_.

### Git commit format
**CLA-123: Add login API**

- CLA: Project code
- 123: Task ID
- Add: Action. Action include: Add, Delete, Fix, Bump, Refactor, Optimize, Reformat, Document
- Add login API: message title, should be short, maximum 50 characters
- The rest is commit detail, called message body. We must use a newline to separate message title and message body
- Do not use full stop at the end of line



## Docker
With simple setup, we should move with Docker Composer. Otherwise, in the case of configuring cluster server, we must use Docker Swarm or Kubernetes.

## Task Mangement


## Tracking Issue

## CI/CD
### Mobile CI
##### Xcode Server

##### fastlane

### Source code CI

### Slack Integration





