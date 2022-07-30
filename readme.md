### Installation

I'm installing Node via [asdf-nodejs](https://github.com/asdf-vm/asdf-nodejs).

```
asdf install
```

Then [installing typescript as a npm package](https://www.typescriptlang.org/download), initially done with:

```
npm install typescript --save-dev
```

Later runs can just use `npm install` to install what is specified in `package-lock.json` automatically.

Installation can be verified with:

```
npx tsc --version
```

Code can be run with:

```
npx tsc MyCode.ts
```