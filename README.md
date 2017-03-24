# cookiecutter-git
**Git Cookiecutter**. Git Repository Project Template!

## Features
- Bare project structure
- License customization
- [Gitignore customization](https://www.gitignore.io/)
- Remote repository creation
  - [GitHub.com as provider](https://github.com/)
  - [GitLab.com as provider](https://gitlab.com/)
- Cross-platform support

### Upcoming
- [Generated change log](https://github.com/skywinder/github-changelog-generator)
- More license choices
- [Bitbucket.org support](https://bitbucket.org/)
- Full coverage testing
- Continuous integration
- First tagged release
- Add logger to hooks ?
- [CodeCommit support](https://aws.amazon.com/codecommit/) ?

## Requirements
- [git](https://git-scm.com/downloads)
- [python](https://www.python.org/downloads/)
- [cookiecutter](https://github.com/audreyr/cookiecutter)

## Usage
    $ cookiecutter gh:webevllc/cookiecutter-git

### Example
See [test-repo](https://github.com/webevllc/test-repo)

    $ tree -a test-repo
    test-repo
    ├── AUTHORS.md
    ├── CHANGELOG.md
    ├── CONTRIBUTING.md
    ├── .git
    ├── .gitignore
    ├── LICENSE
    ├── NOTICE
    ├── README.md
    └── test_pkg
        └── .gitkeep

    2 directories, 8 files

## Development
See [CONTRIBUTING](CONTRIBUTING.md)

## History
See [CHANGELOG](CHANGELOG.md)

## Credits
See [AUTHORS](AUTHORS.md)

## License
See [LICENSE](LICENSE), [NOTICE](NOTICE)
