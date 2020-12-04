# Auto Change Log Generator Demo

#### Fork and Init Your Project
Initialize Libraries
`npm install`
Initialize Project
`npm run init`

#### Do Fake Release Before Changelog
In second command you have to increase version number for future releases. Do Not Forget!!!!!!!!!!!
```
npm run release 0.0.1 && npm run version 0.0.2 
```

#### Generate Changelog and Push
This repo has not binded to remote git account. You will get error when process finished. Because it can not push repo. But changelog will be generated successfully and has committed to git.
```
npm run push
```

#### Commit Formats
```
git commit -m "fix: bla bla error fixed"
git commit -m "feature: bla bla feature added"
git commit -m "break: bla bla breaking error fixed"
```

#### Example Scenario
    - Make any changes in project.
    - Commit your changes with formats.
    - Do fake release
    - Push project
