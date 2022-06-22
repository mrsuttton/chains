# ⛓️ chains

A list of all the chains supported for automatic ABI decoding.

## How to Add Chains

To add your preferred chain to our list, please submit a pull request to add
your chain to the `chains.json` file.

New chains must be in the format of:

```js
${CHAIN_ID} :{
  "apiRoute": ${API_ROUTE},
  "baseUrl": ${BLOCK_EXPLORER_URL},
  "name": ${NETWORK_NAME},
}
```
