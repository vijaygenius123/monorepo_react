# Monorepo With React

## Setup 
1. Run lerna init to setup the monorepo
```bash
npx lerna init
```
2. Update the name in `package.json`
3. Update `lerna.json` to use independent versioning, workspaces and also use npmClient as yarn like below
```json
{
  "version": "independent",
  "npmClient": "yarn",
  "useWorkspaces": true
}
```
