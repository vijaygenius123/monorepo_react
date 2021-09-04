# Monorepo With React

## Setup 
1. Run lerna init to setup the monorepo
```bash
npx lerna init
```
2. Update the name and workspaces in `package.json`
```json
{
  "workspaces": {
    "packages": [
      "packages/**"
    ]
  }
}
```
3. Update `lerna.json` to use independent versioning, workspaces and also use npmClient as yarn like below
```json
{
  "version": "independent",
  "npmClient": "yarn",
  "useWorkspaces": true
}
```
4. Create the applications within the package folder
