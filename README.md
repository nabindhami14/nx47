```sh
yarn create nx-workspace --package-manager=yarn
```

```sh
yarn add -W -D @nx/react
nx g @nx/react:app --name=frontend --directory=apps/frontend --minimal=true --pascalCase=true
```

```sh
nx run frontend:serve
nx run frontend:typecheck
```
