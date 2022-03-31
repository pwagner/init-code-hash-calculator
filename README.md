# init-code-hash-calculator
Calculate the `INIT_CODE_HASH` of a smart contract bytecode (needed for CREATE2 address computation).

```
node src/calc.mjs
```

The example in `src/calc.mjs` uses the contract creation bytecode of SpooksySwap *Pairs* (which is deployed with the `createPair` method of the *Factory*).
You can compare the console output with the `INIT_CODE_HASH` in the SpookySwap SDK: https://github.com/SpookySwap/spookyswap-sdk/blob/master/src/constants.ts#L26
