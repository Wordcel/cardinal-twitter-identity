# Simplified Twitter Cardinal Identity Package


## Installation
```
yarn add cardinal-twitter
```


## Usage
```ts
import { getIdentity } from 'cardinal-twitter';
import { PublicKey } from '@solana/web3.js';

async function main() {
  const publicKey = new PublicKey('...');
  const identity = await getIdentity(publicKey);
  console.log(identity);
  //  Output: {
  //    username: 'elonmusk',
  //    displayImage: '<image_url>',
  //  }
}

```
