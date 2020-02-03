<p align="center">
  <a href="https://github.com/actions/action-label/actions"><img alt="action-label status" src="https://github.com/kitabisa/action-label/workflows/build-test/badge.svg"></a>
</p>

# Action Label

Action for handle pull request label

## Code in Master

Install the dependencies  
```bash
$ yarn install
```

Build the typescript
```bash
$ yarn run build
```

Run the tests :heavy_check_mark:  
```bash
$ yarn test

 PASS  ./main.test.ts
  ✓ throws invalid number (3ms)
  ✓ wait 500 ms (504ms)
  ✓ test runs (95ms)

...
```

## Usage:

Add to workflow.yml 
```yaml
uses: actions/typescript-action@v1
with:
  milliseconds: 1000
```
