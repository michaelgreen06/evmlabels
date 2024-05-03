<p align="center">
  <a><img src="https://raw.githubusercontent.com/dawsbot/evm-labels/v1/docs/img/etherscan.png" title="Logo" width="400"/></a>
</p>
<p align="center">
  <b>
    EVM Labels
  </b>
  <br>
  <i>A public dataset of crypto addresses labeled (<a href="https://etherscan.io/labelcloud">Ethereum and more</a></i>)
  <br>
</p>

<br/>

## Ethereum

<img src="https://raw.githubusercontent.com/dawsbot/evm-labels/v1/docs/img/etherscan.png" width="200"/></a>

<!-- AUTO-GENERATED-CONTENT:START (lastEdited:dataDirectory=etherscan) -->

etherscan was last modified: March 28, 2024

[View labels here](data/etherscan)

<!-- AUTO-GENERATED-CONTENT:END -->

## Arbitrum

<!-- AUTO-GENERATED-CONTENT:START (lastEdited:dataDirectory=arbitrum) -->

arbitrum was last modified: March 28, 2024

[View labels here](data/arbitrum)

<!-- AUTO-GENERATED-CONTENT:END -->

## Optimism

<!-- AUTO-GENERATED-CONTENT:START (lastEdited:dataDirectory=optimism) -->

optimism was last modified: March 28, 2024

[View labels here](data/optimism)

<!-- AUTO-GENERATED-CONTENT:END -->

## Base

<!-- AUTO-GENERATED-CONTENT:START (lastEdited:dataDirectory=basescan) -->

basescan was last modified: March 28, 2024

[View labels here](data/basescan)

<!-- AUTO-GENERATED-CONTENT:END -->

## Binance Smart Chain

<img src="https://raw.githubusercontent.com/dawsbot/evm-labels/v1/docs/img/bscscan.svg" width="200"/></a>

<!-- AUTO-GENERATED-CONTENT:START (lastEdited:dataDirectory=bscscan) -->

bscscan was last modified: April 30, 2024

[View labels here](data/bscscan)

<!-- AUTO-GENERATED-CONTENT:END -->

## Gnosis Chain

<img src="https://raw.githubusercontent.com/dawsbot/evm-labels/v1/docs/img/gnosis.svg" width="200"/></a>

<!-- AUTO-GENERATED-CONTENT:START (lastEdited:dataDirectory=gnosis) -->

gnosis was last modified: April 30, 2024

[View labels here](data/gnosis)

<!-- AUTO-GENERATED-CONTENT:END -->

## Celo

<img src="https://raw.githubusercontent.com/dawsbot/evm-labels/v1/docs/img/celo.svg" width="200"/></a>

<!-- AUTO-GENERATED-CONTENT:START (lastEdited:dataDirectory=celo) -->

celo was last modified: April 12, 2024

[View labels here](data/celo)

<!-- AUTO-GENERATED-CONTENT:END -->

<!-- | Label                                                                                              | CSV                                              | JSON                                               | Updated      |
| -------------------------------------------------------------------------------------------------- | ------------------------------------------------ | -------------------------------------------------- | ------------ |
| [`exchange`](https://etherscan.io/accounts/label/exchange) (Centralized Exchanges)                 | [View CSV](./src/mainnet/exchange/all.csv)       | [View JSON](./src/mainnet/exchange/all.json)       | May 9, 2022  |
| [`phish-hack`](https://etherscan.io/accounts/label/phish-hack) (Phishing/Hacking)                  | [View CSV](./src/mainnet/phish-hack/all.csv)     | [View JSON](./src/mainnet/phish-hack/all.json)     | May 15, 2022 |
| [`genesis`](https://etherscan.io/accounts/label/genesis) (Null/black hole addresses)               | [View CSV](./src/mainnet/genesis/all.csv)        | [View JSON](./src/mainnet/genesis/all.json)        | May 21, 2022 |
| [`token-contract`](https://etherscan.io/accounts/label/token-contract) (ERC-20 and similar tokens) | [View CSV](./src/mainnet/token-contract/all.csv) | [View JSON](./src/mainnet/token-contract/all.json) | May 25, 2022 | -->

More chains coming soon (March/April 2024)

## Q & A

- Where does this data come from?
  - This data is already organized by the kind folks at Etherscan. Unfortunately that data is not accessible for researchers, so we've copied the data out and into a more shareable format here.

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=dawsbot/evm-labels&type=Date)](https://star-history.com/#dawsbot/evm-labels&Date)

<!-- ## Install

```sh
npm install --save evm-labels

# or with yarn
yarn add evm-labels
```

<br/>

## Use

You can install the CSV or JSON manually if you are not a dev. If you want to use this in code:

### Exchange (CEX's)

```js
import { exchange } from "evm-labels";

// A Coinbase hot wallet
const COINBASE_ADDRESS = "0x71660c4005ba85c37ccec55d0c4493e66fe775d3";
exchange.isExchangeAddress(COINBASE_ADDRESS);
// true

const NULL_ADDRESS = "0x0000000000000000000000000000000000000000";
exchange.isExchangeAddress(NULL_ADDRESS);
// false
```

### Phish/Hack (Addresses that performed phishing or hacks)

```js
import { phishHack } from "evm-labels";

// A Nexus Mutual Hacker
const HACKER_ADDRESS = "0x09923e35f19687a524bbca7d42b92b6748534f25";
phishHack.isPhishHackAddress(HACKER_ADDRESS);
// true

const NULL_ADDRESS = "0x0000000000000000000000000000000000000000";
phishHack.isPhishHackAddress(NULL_ADDRESS);
// false
```

### Genesis

```js
import { genesis } from "evm-labels";

const GENESIS_ADDRESS = "0x0000000000000000000000000000000000000002";
genesis.isGenesisAddress(GENESIS_ADDRESS);
// true

const OATHER_ADDRESS = "0x09923e35f19687a524bbca7d42b92b6748534f25";
genesis.isGenesisAddress(OATHER_ADDRESS);
// false
```

### Token Contract

```js
import { tokenContract } from "evm-labels";

const TOKEN_CONTRACT_ADDRESS = "0x5dd57da40e6866c9fcc34f4b6ddc89f1ba740dfe";
tokenContract.isTokenContractAddress(TOKEN_CONTRACT_ADDRESS);
// true

const OATHER_ADDRESS = "0x0000000000000000000000000000000000000002";
tokenContract.isTokenContractAddress(OATHER_ADDRESS);
// false
```

<br/>

## Contributing

The pulling method from Etherscan involves running a TypeScript file locally which performs the browser automation and data pulling + writing to your local filesystem.

The file of concern is `scripts/puppeteer-fetch-all.ts` and can be executed with `npx tsx scripts/puppeteer-fetch-all.ts` -->
