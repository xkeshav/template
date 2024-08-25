# Docs

This is alternative location to save your document for a repository.

## Files Structure

below are files and folder information in this template repository, you can remove files/folder as per your need.

### inside .vscode folder

- `extensions.json` --> recommended vs code extensions.
- `cspell.json` --> used by code spell checker extension.
- `dictionaries/` ---> project specific words can be stored under the files, it is used by code spell checker.
- `javascriptreact.json` --> custom react snippets with keyboard shortcuts for useState `us` and basic component file structure `rfc`
- `pkg.json` --> just a javascript snippet which generate package.json code in any js file and you can use to generate _package.json_
- `settings.json` --> basic vs code settings; you can use it in your user settings

### inside .github folder

having basic health files and

- `workflows/` --> folder have one GitHub Action which validate markdown files on push

Apart from that there are few files on project root

- `package.json` --> a sample package.json which need to modify as per your project requirement

- `.markdownlint.json` --> file require for markdownlint extension

- `.template-code-workspace` --> file have few basic and useful vs code settings; you can change as per your project requirement.
- `.editorconfig` --> config regarding files to use tab/space or end of file etc.
- `.prettierrc` --> required config for vscode-prettier extension

### How to run

although this is just a template repository but added package.json and one file just for fun.

run below command in terminal

```bash
> npm install
> npm run start
```

and see the output in terminal.
