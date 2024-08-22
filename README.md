# Template Repository

This is [readme file][readme] of template repository.

having

- default health files
- _package.json_ boilerplate ( replace _project_ with your choice)
- .vscode folder have vs code related settings such as
  - code snippets
  - user / workspace settings file
  - recommended extensions
  - dictionaries (cSpell related)

## Pre-requisite

- Node 18+
- VS Code IDE

## How to start

- clone/fork the repo
- make changes in package.json

```sh
> npm install
```

then

```sh
> npm run start
```

## Folder Tree

Below are the complete folder structure of this repo

```bash
.
├── .editorconfig
├── .github
│   ├── CODEOWNERS
│   ├── CODE_OF_CONDUCT.md
│   ├── CONTRIBUTING.md
│   ├── DISCUSSION_TEMPLATE
│   │   ├── announcements.yml
│   │   └── ideas.yml
│   ├── FUNDING.yml
│   ├── ISSUE_TEMPLATE
│   │   ├── BUG_FORM.yml
│   │   ├── ENHANCEMENT.yml
│   │   ├── FEATURE_REQUEST.md
│   │   ├── QUESTION.md
│   │   └── config.yml
│   ├── PULL_REQUEST_TEMPLATE.md
│   ├── SECURITY.md
│   └── SUPPORT.md
├── .gitignore
├── .tree
├── .vscode
│   ├── cspell.json
│   ├── dictionaries
│   │   ├── project-words.txt
│   │   └── team-member.txt
│   ├── extensions.json
│   ├── javascriptreact.json
│   ├── markdownlint.json
│   ├── pkg.json
│   ├── settings.json
│   ├── tasks.json
│   └── template.code-snippets
├── CHANGELOG.md
├── LICENSE
├── README.md
├── docs
│   └── README.md
├── package.json
├── src
│   └── index.js
├── template.code-workspace
└── tree

8 directories, 35 files


```

## Note

Please update the readme as per your project.

<!-- References -->

[readme]: https://github.com/xkeshav/project/blob/main/README.md
