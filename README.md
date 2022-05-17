### DESCRIPTION

The sample source code build a subgraph for CryptoPunks by me. It is the basic code built on the documents of The Graph.

### INSTALL GRAPH CLI

You can install Graph CLI with either npm or yarn.

- Install graph cli using npm

```bash
npm install -g @graphprotocol/graph-cli
```

- Install graph cli using yarn

```bash
yarn global add @graphprotocol/graph-cli
```

### INIT

Initialize your subgraph.

- Initialize subgraph

```bash
graph init --studio <${Subgraph Name}>
```

### AUTH & DEPLOY

Authenticate within the CLI, build and deploy your subgraph to the Studio.

- Authenticate in cli

```bash
graph auth --studio <${Deploy Key in Subgraph Studio}>
```

- Build Subgraph

```bash
graph codegen && graph build
```

- Deploy Subgraph

```bash
graph deploy --studio <${Subgraph Name}>
```
