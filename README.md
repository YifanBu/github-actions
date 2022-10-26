# github-actions
Use Github Actions to automate the CI/CD workflow of a React application
# Create React App
https://create-react-app.dev/


### Test
the test file is in src/App.test.js

`CI=true npm run test`

`npm run test -- --coverage`

### Build

`npm run build`
# Deploy
### Surge
A platform that provides static website hosting service.

https://surge.sh/

`surge /build`

domain: https://hellish-stone.surge.sh/

### Prettier
A tool that checks for code formatting rules
https://prettier.io/

`npm install --save-dev --save-exact prettier`

`npx prettier --check "**/*.js"`

`npx prettier --write "**/*.js"`
# Workflow
1. Feature1 -> Pull Request -> Run Workflow -> Develop -> Run Workflow
2. Develop -> Pull Request -> Run Workflow -> Master -> Run Workflow

### Code Owners
https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners

.github/CODEOWNERS
### npm ci
https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners

### Caching Dependencies
https://docs.github.com/en/actions/using-workflows/caching-dependencies-to-speed-up-workflows
https://github.com/actions/cache

### Semantic Versioning
\<Major Version>.\<Minor Version>.\<Patch Version>
https://semver.org/
https://github.com/semantic-release/semantic-release

### Conventional Commit
https://www.conventionalcommits.org/en/v1.0.0/
https://github.com/conventional-changelog/commitlint
https://github.com/commitizen/cz-cli

### Codecov
An online service where you can share code coverage reports.
https://about.codecov.io/

# Notification

### Slack Message
Slack messages will be sent when:
1. Job Failure
2. Issue Created
3. Release Created

# Authors and acknowledgment
The content is created by following Ali Alaa's Course: The Complete GitHub Actions & Workflows Guide

