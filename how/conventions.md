# conventions

- [conventions](#conventions)
  - [project management](#project-management)
  - [issues](#issues)
  - [pull requests](#pull-requests)
  - [commits](#commits)
  - [branches](#branches)
  - [releases](#releases)

## project management

TODO: spec for working with github projects

- since issues are getting imported this mainly concerns when to start and close projects on a given repository and how to name them

## issues

TODO: spec for creating and working with issues. this will include:

- how to write issues, issue templates, issue labels
- when to open and close issues
- how to make use of github's automation syntax inside issue titles and comments
- etc.

## pull requests

TODO: spec for creating pull requests and how to work with them:

- when to open PR
- naming conventions for title and description
- PR templates
- how to label and assign PRs
- how to review PRs
- when to merge PRs
- how to merge PRs, including rebase/squash and naming

## commits

[we use the **conventional commits** spec](https://www.conventionalcommits.org/en/v1.0.0/)

```text
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

..with the [commitlint reccomended type expansion](https://github.com/conventional-changelog/commitlint/tree/master/%40commitlint/config-conventional):

- `build:`
- `chore:`
- `ci:`
- `docs:`
- `style:`
- `refactor:`
- `perf:`
- `test:`

## branches

[we use the git flow branching model](https://nvie.com/posts/a-successful-git-branching-model/):

![image of git flow branching diagram](https://nvie.com/img/git-model@2x.png)

## releases

[We version our software based on the semantic versioning specification](https://semver.org):

>Given a version number `MAJOR.MINOR.PATCH`, increment the:
>
>- `MAJOR` version when you make incompatible API changes,
>- `MINOR` version when you add functionality in a backwards compatible manner, and
>- `PATCH` version when you make backwards compatible bug fixes.
>
>Additional labels for pre-release and build metadata are available as extensions to the `MAJOR.MINOR.PATCH` format.
