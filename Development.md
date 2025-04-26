# Development

## Install depedencies

```
npm install
```

or

```
yarn install
```


## Build extension

```
npm run build
```

or

```
yarn build
```


## Package the extension into a .vsix file

for installing in your main VSCode


If you want to install your customized extension into your main VSCode instance:

1. Install the VSCE tool:

```bash
npm install -g @vscode/vsce

```

2. Package the extension:

```bash
vsce package

```

This will generate a .vsix file.

## Install the .vsix file into VSCode

```
code --install-extension <extension-name>.vsix

```

Or in VSCode:

Go to `Extensions` → click `...` → choose `Install from VSIX...`

