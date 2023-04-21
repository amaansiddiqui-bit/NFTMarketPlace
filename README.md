

## Getting Started

npm run dev 

## Install initial project

```bash
npm install 
```

```bash
npm run dev 
``` 

---------------------------------------

## For adding your thirweb account's contacts

go inside `const/addresses.ts` file and change variables:

```export const MARKETPLACE_ADDRESS = "your-address";```

```export const NFT_COLLECTION_ADDRESS = "your-address";```


-----------------------------------------

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

On `pages/_app.tsx`, you'll find our `ThirdwebProvider` wrapping your app, this is necessary for our [hooks](https://portal.thirdweb.com/react) and
[UI Components](https://portal.thirdweb.com/ui-components) to work.

### Deploy to IPFS

Deploy a copy of your application to IPFS using the following command:

```bash
yarn deploy
```


