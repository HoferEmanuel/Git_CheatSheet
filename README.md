# Content
- [What does Git do?](#gitinfo)
  - [General](#general)
  - [Submodules](#submodules)

<hr/>

# <a name="gitinfo">What does Git do?</a>
- Project-Management with repositories.
- Work on a local copy by cloning a repository.
- Control and track changes by stagging and committing.
- Branch and Merge to allow for work on different parts and versions of a project
- Pull the latest version of the project to a local copy
- Push local updates to the main project

<sup>src.: W3Schools

# <a name="general">General</a>

## check git-version
```
git --version
```

### get usefull command list
```
git help
```

### add Readme
```
git add Readme.rm
```

### get last commit changes
```
git diff
```

### show commits-overview
<sub>open repo-folder in cmd first</sub>
```
git log
```
# <a name="submodules">Submodules</a>
<hr/>

### add a submodule
```
git submodule add https://github.com/<user>/<repo>
```
### refresh submodule
```
git submodule update --init
```


