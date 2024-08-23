# Template Repository

![Template][template]
![License][license]
![Open Issues][issues]
![Commit Count][commits]
![Total Pull Request][PR]

This is a template repository which contains

- community health files under mostly under `.github`
- _package.json_ boilerplate
- github action under `.github/workflows` for markdown file validity
- `.vscode` folder which have
  - code snippets
  - user / workspace settings file
  - recommended extensions
  - project dictionaries

## Pre-requisite

- Node 18+
- VS Code IDE

## How to use this Template repository

- Open this [repository][repo] in GitHub
- Click on `use this template` tab; near _star_ tab
- Make necessary changes in
  - _package.json_
    - replace _template_ with your project name.
  - markdown files under _.github_ folder
    - change contact email address and url wherever required.

## Folder Tree

<details>
<summary>
  <mark>Repository Folder Structure</mark>
</summary>

```bash
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
│   ├── SUPPORT.md
│   └── workflows
│       └── markdown-lint.yml
├── .gitignore
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
├── public
│   └── assets
│       └── images
├── src
│   └── index.js
├── template.code-workspace
└── tree
12 directories, 36 files

```

</details>

---

## License

This project is licensed under the [MIT License](LICENSE).

---

> [!Important]
> Please update the readme and package.json as per your project.

<!-- References -->

[template]: https://badgen.net/static/github/template?icon=github
[repo]: https://github.com/xkeshav/template
[license]: https://badgen.net/github/license/xkeshav/template
[issues]: https://badgen.net/github/open-issues/xkeshav/template
[PR]: https://badgen.net/github/prs/xkeshav/template
[commits]: https://badgen.net/github/commits/xkeshav/template/main?color=green
