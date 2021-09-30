# Date Picker Svelte

Date and time picker for Svelte

[Demo](https://date-picker-svelte.kasper.space/demo)

[Documentation](https://date-picker-svelte.kasper.space/docs)

## Dev instructions

### Get started

1. Install Node.js (v14 works)
2. Run `npm install`

### Commands

- `npm run dev`: Start site in dev mode
- `npm run build`: Build package and site
- `npm run build:package`: Build package
- `npm run build:site`: Build site
- `npm run preview`: Preview production site
- `npm run check`: Run `svelte-check`
- `npm run lint`: Lint

### Publish new version

1. Update `CHANGELOG.md`
2. Check for errors
    ```
    npm run check
    ```
3. Bump the version number
    ```
    npm version --no-git-tag <version>
    ```
4. Generate the package
    ```
    npm run build:package
    ```
5. Publish the package
    ```
    npm publish ./package
    ```
6. Commit with a tag in format "v#.#.#"
7. Create GitHub release with release notes