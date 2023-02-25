# NPM Hacks and Tricks

## Useful commands

To init a npm project skipping the wizard.

```bash
npm init -y
```

Opens the package official website in the browser.

```bash
npm home <package>
```

Looks up where a package is used in the project.

```bash
npx npm-why <package>
```

Goes to the repository issues section.

```bash
npm bugs <package>
```

Checks which packages are out of date.

```bash
npm outdated
```

Shows the NPM Task List for the projects.

```bash
npx ntl
```

Checks the disk size of a package before install it.

```bash
npx npm-size <package>
```

Lists the packages and dependencies used in a project. The depth level flag can
be included, where `0` only shows the project direct dependencies.

```bash
npm list --depth=<N>
```

Tries to reduce duplicated dependencies in the `node_modules`.

```bash
npm dedupe
```

Checks security issues in the existing project dependencies. The `fix` parameter
can be included to automatically fix the issues.

```bash
npm audit
```

Checks if there is connection with the NPM registry to download packages,
download binaries, Node and NPM versions, Git binaries being used or if there's
any permissions issue.
```bash
npm doctor
```

Shows the list of scripts of the projects

```bash
npm run
```

Shows package information
```bash
npm view <package>
```

Checks and delete dependencies unlisted in the `package.json`.

```bash
npm prune
```

# Useful utilities
These utilities must be installed globally with `npm install -g`.

- `npm-check`: Checks outdated package versions interactively.


