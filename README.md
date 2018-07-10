- Simple repo for reporting issue with version >=3.0.64 that is causing error for `module-alias` package.
- It's working fine with prior versions.
- Error on macOS (seems working on Windows):
- Reported on: https://github.com/standard-things/esm/issues/499

```
Error: Cannot find module 'module'
```

- To verify:

```
npm start
```
