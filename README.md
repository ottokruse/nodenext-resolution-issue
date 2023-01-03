# Reproduce TypeScript Issue with Module Resolution NodeNext

Issue: https://github.com/microsoft/TypeScript/issues/51996

## Steps to reproduce

Clone repo:

```shell
git clone https://github.com/ottokruse/nodenext-resolution-issue
cd nodenext-resolution-issue
```

Install TypeScript:

```shell
npm i
```

Compile:

```shell
npx tsc # Throws error
```

### Workaround

Edit `tsconfig.json` and change `moduleResolution` to `Node`.
