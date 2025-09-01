# nodejs_templates

---

## 🌳 Git flow

### Branch naming

In general are patterns mostly looks like this:

```
<type>/<branch-name-with-spaces-denoted-by-dashes>

Examples:

feature/add-feature
bugfix/fix-feature
```

### Conventional Commits [read more](https://www.conventionalcommits.org/)

In general the pattern mostly looks like this:

```
<type>[optional scope]: <description>

Examples:

feat: add new feature
feat([optional scope]): add new feature
```

Allowed Types:

-   build - Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)
-   ci - Changes to our CI configuration files and scripts (example scopes: Travis, Circle, BrowserStack, SauceLabs)
-   changelog - Used for updating the release notes in CHANGELOG.md
-   chore - Changes to the build process or auxiliary tools and libraries such as documentation generation
-   docs - Documentation only changes
-   feat - A new feature
-   fix - A bug fix
-   packaging - Used for changes that change the npm package layout in all of our packages, e.g. public path changes, package.json changes done to all packages, d.ts file/format changes, changes to bundles, etc.
-   perf - A code change that improves performance
-   refactor - A code change that neither fixes a bug nor adds a feature
-   revert - A code change that neither fixes a bug nor adds a feature
-   style - Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
-   test - Adding missing tests or correcting existing tests
-   tmp - temporary commit

---

## Contributing

PRs and issues are welcome 🙌\
Suggested workflow:

1.  Branch/fork.
2.  Changes in the respective package under `packages/`.
3.  Bump versions and `CHANGELOG.md` (if used).
4.  Run `pnpm -C examples/... lint/test` for both examples.
5.  Submit PR with clear motivation.

---

## License

MIT © NikolaiVerbitskii
