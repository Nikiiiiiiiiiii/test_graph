## Description

Fork subgraph <a href="https://github.com/0xcap/capv3-subgraph" target="_blank">capv3-subgraph</a> from <a href="https://www.cap.finance/" target="_blank">CAP Finance</a>.

## Requirements

```
# package manager
yarn or npm
```

To create and deploy a subgraph, you need <a href="https://www.npmjs.com/package/@graphprotocol/graph-cli" target="_blank">a graph-cli</a>.

Create an account in <a href="https://thegraph.com/docs/en/studio/subgraph-studio/" target="_blank">Subgraph Studio</a>. This account will be used to deploy and publish the subgraph.

## Initialization

```bash
# yarn
$ yarn install

# npm
$ npm install
```

## Deploy subgraph

<a href="https://thegraph.com/docs/en/studio/deploy-subgraph-studio/">How to deploy a subgraph in the Subgraph Studio?</a>

Before deployment, you need to create a subgraph in the Subgraph Studio.

Run these commands in the subgraph folder.

```bash
$ graph codegen

$ graph build
```

Authenticate and deploy your subgraph. The deploy key and subgraph slug can be found on the Subgraph page in Subgraph Studio.

```bash
$ graph auth --studio <DEPLOY_KEY>

$ graph deploy --studio <SUBGRAPH_SLUG>
```

After that publish your subgraph to the decentralized network (<a href="https://thegraph.com/docs/en/developer/publish-subgraph/" target="_blank">instructions here</a>).
