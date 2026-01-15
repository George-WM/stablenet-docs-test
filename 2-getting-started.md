[Index your code with Devin](/private-repo)

[DeepWiki](/)

[DeepWiki](/)

[stable-net/go-stablenet](https://github.com/stable-net/go-stablenet "Open repository")

[

Index your code with

Devin

](/private-repo)Edit WikiShare

Last indexed: 29 November 2025 ([422cf1](https://github.com/stable-net/go-stablenet/commits/422cf168))

-   [StableNet Overview](/stable-net/go-stablenet/1-stablenet-overview)
-   [Getting Started](/stable-net/go-stablenet/2-getting-started)
-   [Installation and Building](/stable-net/go-stablenet/2.1-installation-and-building)
-   [Node Configuration](/stable-net/go-stablenet/2.2-node-configuration)
-   [Genesis Setup and Network Types](/stable-net/go-stablenet/2.3-genesis-setup-and-network-types)
-   [Core Architecture](/stable-net/go-stablenet/3-core-architecture)
-   [Node Initialization and Lifecycle](/stable-net/go-stablenet/3.1-node-initialization-and-lifecycle)
-   [Blockchain Management](/stable-net/go-stablenet/3.2-blockchain-management)
-   [State Management](/stable-net/go-stablenet/3.3-state-management)
-   [Transaction Pool](/stable-net/go-stablenet/3.4-transaction-pool)
-   [Transaction Types and Encoding](/stable-net/go-stablenet/3.5-transaction-types-and-encoding)
-   [Consensus and Block Production](/stable-net/go-stablenet/4-consensus-and-block-production)
-   [Anzeon WBFT Consensus Protocol](/stable-net/go-stablenet/4.1-anzeon-wbft-consensus-protocol)
-   [Block Production and Mining](/stable-net/go-stablenet/4.2-block-production-and-mining)
-   [Validator Management](/stable-net/go-stablenet/4.3-validator-management)
-   [Governance System](/stable-net/go-stablenet/5-governance-system)
-   [System Contracts Overview](/stable-net/go-stablenet/5.1-system-contracts-overview)
-   [NativeCoinAdapter Contract](/stable-net/go-stablenet/5.2-nativecoinadapter-contract)
-   [GovValidator Contract](/stable-net/go-stablenet/5.3-govvalidator-contract)
-   [Minting and Burning Governance](/stable-net/go-stablenet/5.4-minting-and-burning-governance)
-   [Mint and Burn Protocol](/stable-net/go-stablenet/5.5-mint-and-burn-protocol)
-   [Transaction Processing](/stable-net/go-stablenet/6-transaction-processing)
-   [Transaction Lifecycle](/stable-net/go-stablenet/6.1-transaction-lifecycle)
-   [State Transitions](/stable-net/go-stablenet/6.2-state-transitions)
-   [EVM Execution](/stable-net/go-stablenet/6.3-evm-execution)
-   [Gas Fee Policy](/stable-net/go-stablenet/6.4-gas-fee-policy)
-   [Networking](/stable-net/go-stablenet/7-networking)
-   [P2P Server and Peer Management](/stable-net/go-stablenet/7.1-p2p-server-and-peer-management)
-   [Peer Discovery](/stable-net/go-stablenet/7.2-peer-discovery)
-   [Chain Synchronization](/stable-net/go-stablenet/7.3-chain-synchronization)
-   [Protocol Handlers](/stable-net/go-stablenet/7.4-protocol-handlers)
-   [RPC API](/stable-net/go-stablenet/8-rpc-api)
-   [API Services and Namespaces](/stable-net/go-stablenet/8.1-api-services-and-namespaces)
-   [Event Filtering and Subscriptions](/stable-net/go-stablenet/8.2-event-filtering-and-subscriptions)
-   [Transaction Submission and Signing](/stable-net/go-stablenet/8.3-transaction-submission-and-signing)
-   [Storage Architecture](/stable-net/go-stablenet/9-storage-architecture)
-   [Database Layer](/stable-net/go-stablenet/9.1-database-layer)
-   [State Tries and Merkle Patricia Trees](/stable-net/go-stablenet/9.2-state-tries-and-merkle-patricia-trees)
-   [Snapshots and Caching](/stable-net/go-stablenet/9.3-snapshots-and-caching)
-   [Development Tools](/stable-net/go-stablenet/10-development-tools)
-   [Building and CI/CD](/stable-net/go-stablenet/10.1-building-and-cicd)
-   [devp2p Tools](/stable-net/go-stablenet/10.2-devp2p-tools)
-   [Data Import and Export Utilities](/stable-net/go-stablenet/10.3-data-import-and-export-utilities)
-   [Testing Framework](/stable-net/go-stablenet/10.4-testing-framework)
-   [JavaScript Console](/stable-net/go-stablenet/10.5-javascript-console)
-   [Operations Guide](/stable-net/go-stablenet/11-operations-guide)
-   [Network Types and Deployment](/stable-net/go-stablenet/11.1-network-types-and-deployment)
-   [Validator Operations](/stable-net/go-stablenet/11.2-validator-operations)
-   [Node Monitoring and Maintenance](/stable-net/go-stablenet/11.3-node-monitoring-and-maintenance)

Menu

# Getting Started

Relevant source files

-   [.dockerignore](https://github.com/stable-net/go-stablenet/blob/422cf168/.dockerignore)
-   [.golangci.yml](https://github.com/stable-net/go-stablenet/blob/422cf168/.golangci.yml)
-   [.travis.yml](https://github.com/stable-net/go-stablenet/blob/422cf168/.travis.yml)
-   [Dockerfile](https://github.com/stable-net/go-stablenet/blob/422cf168/Dockerfile)
-   [Dockerfile.alltools](https://github.com/stable-net/go-stablenet/blob/422cf168/Dockerfile.alltools)
-   [Makefile](https://github.com/stable-net/go-stablenet/blob/422cf168/Makefile)
-   [accounts/abi/doc.go](https://github.com/stable-net/go-stablenet/blob/422cf168/accounts/abi/doc.go)
-   [appveyor.yml](https://github.com/stable-net/go-stablenet/blob/422cf168/appveyor.yml)
-   [build/checksums.txt](https://github.com/stable-net/go-stablenet/blob/422cf168/build/checksums.txt)
-   [build/ci.go](https://github.com/stable-net/go-stablenet/blob/422cf168/build/ci.go)
-   [cmd/utils/flags.go](https://github.com/stable-net/go-stablenet/blob/422cf168/cmd/utils/flags.go)
-   [core/chain\_makers.go](https://github.com/stable-net/go-stablenet/blob/422cf168/core/chain_makers.go)
-   [core/genesis.go](https://github.com/stable-net/go-stablenet/blob/422cf168/core/genesis.go)
-   [core/genesis\_alloc.go](https://github.com/stable-net/go-stablenet/blob/422cf168/core/genesis_alloc.go)
-   [core/genesis\_test.go](https://github.com/stable-net/go-stablenet/blob/422cf168/core/genesis_test.go)
-   [core/state/pruner/pruner.go](https://github.com/stable-net/go-stablenet/blob/422cf168/core/state/pruner/pruner.go)
-   [eth/backend.go](https://github.com/stable-net/go-stablenet/blob/422cf168/eth/backend.go)
-   [eth/ethconfig/config.go](https://github.com/stable-net/go-stablenet/blob/422cf168/eth/ethconfig/config.go)
-   [eth/ethconfig/gen\_config.go](https://github.com/stable-net/go-stablenet/blob/422cf168/eth/ethconfig/gen_config.go)
-   [ethclient/simulated/wbft\_backend.go](https://github.com/stable-net/go-stablenet/blob/422cf168/ethclient/simulated/wbft_backend.go)
-   [internal/build/env.go](https://github.com/stable-net/go-stablenet/blob/422cf168/internal/build/env.go)
-   [internal/build/gotool.go](https://github.com/stable-net/go-stablenet/blob/422cf168/internal/build/gotool.go)
-   [internal/build/util.go](https://github.com/stable-net/go-stablenet/blob/422cf168/internal/build/util.go)
-   [miner/miner.go](https://github.com/stable-net/go-stablenet/blob/422cf168/miner/miner.go)
-   [miner/miner\_test.go](https://github.com/stable-net/go-stablenet/blob/422cf168/miner/miner_test.go)
-   [miner/worker.go](https://github.com/stable-net/go-stablenet/blob/422cf168/miner/worker.go)
-   [miner/worker\_test.go](https://github.com/stable-net/go-stablenet/blob/422cf168/miner/worker_test.go)
-   [params/bootnodes.go](https://github.com/stable-net/go-stablenet/blob/422cf168/params/bootnodes.go)
-   [params/config.go](https://github.com/stable-net/go-stablenet/blob/422cf168/params/config.go)

This guide provides an introduction to installing, building, and running your first StableNet node. It covers the essential prerequisites, build process, and initial node setup to get you operational quickly.

For detailed build instructions and CI/CD pipeline information, see [Installation and Building](/stable-net/go-stablenet/2.1-installation-and-building). For comprehensive configuration options, see [Node Configuration](/stable-net/go-stablenet/2.2-node-configuration). For genesis block creation and customization, see [Genesis Setup](/stable-net/go-stablenet/2.3-genesis-setup-and-network-types).

* * *

## Overview

StableNet is a stablecoin-focused blockchain that uses the WBFT (Wemix Byzantine Fault Tolerance) consensus engine, referred to as "Anzeon" in this implementation. The primary executable is `gstable`, which functions as both a full node and validator. Unlike standard Ethereum, StableNet requires specific genesis configuration to deploy governance contracts at block 0 and initialize the validator set.

* * *

## Prerequisites

### Required Dependencies

| Dependency | Minimum Version | Purpose |
| --- | --- | --- |
| Go | 1.19 or later | Building all executables |
 -> Go | 1.20 or later | Building all executables
| C Compiler | gcc/clang | Compiling C dependencies (CGO) |
| Git | Any recent | Cloning repository |

**Hardware Requirements:**

| Configuration | CPU | RAM | Storage | Network |
| --- | --- | --- | --- | --- |
| Minimum | 2+ cores | 4GB | 1TB | 8 Mbps |
| Recommended | 4+ cores | 16GB+ | High-performance SSD 1TB+ | 25+ Mbps |

Sources: [README.md269-283](https://github.com/stable-net/go-stablenet/blob/422cf168/README.md#L269-L283)

* * *

## Build Process

### Building from Source

The build system is managed through `Makefile` and `build/ci.go`. The primary build targets are:

**Build Process Flow**

User

make gstable

go run build/ci.go install

doInstall()

Parse command flags  
\-arch, -cc, -static

build.Env()  
Get git commit, branch

build.GoToolchain  
Configure GOARCH, CC

buildFlags()  
Set ldflags, tags

\-X version.gitCommit  
\-X version.gitDate

\-trimpath

\-tags urfave\_cli\_no\_docs,ckzg

go build

build/bin/gstable

**Build the main `gstable` executable:**

```
make gstable
```

This invokes [build/ci.go192-246](https://github.com/stable-net/go-stablenet/blob/422cf168/build/ci.go#L192-L246) which:

1.  Parses flags via `flag.CommandLine.Parse()` to handle `-arch`, `-cc`, `-static` options
2.  Loads `build.Env()` from [internal/build/env.go29-100](https://github.com/stable-net/go-stablenet/blob/422cf168/internal/build/env.go#L29-L100) to extract git metadata
3.  Configures `build.GoToolchain` with target architecture and C compiler
4.  Generates `buildFlags()` at [build/ci.go248-279](https://github.com/stable-net/go-stablenet/blob/422cf168/build/ci.go#L248-L279) including:
    -   `-ldflags` with git commit and date from `version` package
    -   `-trimpath` to remove local path information
    -   `-tags urfave_cli_no_docs,ckzg` for CLI optimization and KZG support
5.  Outputs to `build/bin/gstable` via `executablePath()` helper

**Build all executables:**

```
make all
```

This builds all packages found by `build.FindMainPackages("./cmd")` at [internal/build/util.go189-206](https://github.com/stable-net/go-stablenet/blob/422cf168/internal/build/util.go#L189-L206): `gstable`, `bootnode`, `clef`, `abigen`, `evm`, `rlpdump`, `devp2p`, and `genesis_generator`.

Sources: [Makefile16-30](https://github.com/stable-net/go-stablenet/blob/422cf168/Makefile#L16-L30) [build/ci.go192-246](https://github.com/stable-net/go-stablenet/blob/422cf168/build/ci.go#L192-L246) [build/ci.go248-279](https://github.com/stable-net/go-stablenet/blob/422cf168/build/ci.go#L248-L279) [internal/build/env.go29-100](https://github.com/stable-net/go-stablenet/blob/422cf168/internal/build/env.go#L29-L100) [internal/build/util.go189-206](https://github.com/stable-net/go-stablenet/blob/422cf168/internal/build/util.go#L189-L206)

* * *

### Docker Build

Docker images are built using multi-stage builds as defined in [Dockerfile1-45](https://github.com/stable-net/go-stablenet/blob/422cf168/Dockerfile#L1-L45):

**Docker Build Flow**

Dockerfile

FROM golang:1.22-alpine AS builder

RUN apk add gcc musl-dev  
linux-headers git ca-certificates

Install GitHub/proxy.golang.org certs  
via openssl s\_client

COPY go.mod go.sum

RUN go mod download

ADD . /go-ethereum

RUN go run build/ci.go install -static ./cmd/gstable

build/bin/gstable

FROM alpine:latest

COPY ca-certificates

COPY --from=builder  
/go-ethereum/build/bin/gstable

EXPOSE 8545 8546

EXPOSE 30303 30303/udp

ENTRYPOINT gstable

Build and run:

```
docker build -t stablenet/gstable .
docker run -d -p 8545:8545 -p 30303:30303 stablenet/gstable
```

The `-static` flag in [Dockerfile28](https://github.com/stable-net/go-stablenet/blob/422cf168/Dockerfile#L28-L28) produces a statically-linked binary via [build/ci.go264-270](https://github.com/stable-net/go-stablenet/blob/422cf168/build/ci.go#L264-L270) setting `-extldflags '-static'` for Linux builds.

For all tools (including `bootnode`, `clef`, etc.), use [Dockerfile.alltools1-44](https://github.com/stable-net/go-stablenet/blob/422cf168/Dockerfile.alltools#L1-L44) which builds all packages without the `./cmd/gstable` restriction.

Sources: [Dockerfile1-45](https://github.com/stable-net/go-stablenet/blob/422cf168/Dockerfile#L1-L45) [Dockerfile.alltools1-44](https://github.com/stable-net/go-stablenet/blob/422cf168/Dockerfile.alltools#L1-L44) [build/ci.go264-270](https://github.com/stable-net/go-stablenet/blob/422cf168/build/ci.go#L264-L270)

* * *

## Executables Overview

The build process generates several key executables:

| Executable | Purpose | Location |
| --- | --- | --- |
| gstable | Main node client (full node, validator, RPC server) | cmd/gstable |
| genesis_generator | Interactive genesis file generation tool | cmd/genesis_generator |
| bootnode | Lightweight bootstrap node for peer discovery | cmd/bootnode |
| clef | External account signing tool | cmd/clef |
| abigen | Generates Go bindings from Solidity contracts | cmd/abigen |
| evm | EVM bytecode execution utility | cmd/evm |
| devp2p | P2P network diagnostic tools | cmd/devp2p |

Sources: [README.md246-261](https://github.com/stable-net/go-stablenet/blob/422cf168/README.md#L246-L261) [build/ci.go64-111](https://github.com/stable-net/go-stablenet/blob/422cf168/build/ci.go#L64-L111)

* * *

## Node Initialization

### Generating a Genesis File

StableNet requires a genesis configuration with Anzeon consensus settings. Use the interactive `genesis_generator` tool:

```
./build/bin/genesis_generator
```

genesis.jsonValidator Setupgenesis\_generatorUsergenesis.jsonValidator Setupgenesis\_generatorUseralt\[Single Node\]\[Multi Node\]Run genesis\_generatorChoose consensus (default: Anzeon)Select "1" (Anzeon)Single-node or multi-node?Select network typeEnter nodekey pathProvide nodekey filederiveAccount(nodekey)address + BLS public keyGenerate with 1 validatorEnter validator addressesProvide address + BLS keysEnter quorumProvide quorum valueGenerate with N validatorsWrite genesis.json

The generator creates a `genesis.json` with:

-   `config.anzeon.init.validators` - Initial validator addresses for epoch 1
-   `config.anzeon.init.blsPublicKeys` - BLS keys for consensus signing
-   `config.anzeon.systemContracts` - GovValidator, NativeCoinAdapter, GovMinter, GovMasterMinter, GovCouncil configuration

Sources: [cmd/genesis\_generator/genesis\_generator.go76-169](https://github.com/stable-net/go-stablenet/blob/422cf168/cmd/genesis_generator/genesis_generator.go#L76-L169) [cmd/genesis\_generator/genesis\_generator.go257-295](https://github.com/stable-net/go-stablenet/blob/422cf168/cmd/genesis_generator/genesis_generator.go#L257-L295)

* * *

### Manual Genesis Configuration

For production deployments, manually edit the genesis file. Critical Anzeon configuration structure:

```
{
  "config": {
    "chainId": 8282,
    "anzeon": {
      "wbft": {
        "requestTimeoutSeconds": 2,
        "blockPeriodSeconds": 1,
        "epochLength": 10,
        "proposerPolicy": 0
      },
      "init": {
        "validators": ["0xaa5faa65e9cc0f74a85b6fdfb5f6991f5c094697"],
        "blsPublicKeys": ["0xaec493af8fa358a...b3478b9b"]
      },
      "systemContracts": {
        "govValidator": {
          "address": "0x0000000000000000000000000000000000001001",
          "params": {
            "validators": "0xaa5faa65e9cc0f74a85b6fdfb5f6991f5c094697",
            "blsPublicKeys": "0xaec493af8fa358a...b3478b9b",
            "members": "0xC3C49d11659170e525c3ed3E0D4560d485EF9229",
            "quorum": "1"
          }
        }
      }
    }
  }
}
```

**Key Distinction:**

-   `anzeon.init` - Validators for **epoch 1 only** (blocks 1-10)
-   `systemContracts.govValidator` - Validators from **epoch 2 onwards** (blocks 11+)

Sources: [README.md412-481](https://github.com/stable-net/go-stablenet/blob/422cf168/README.md#L412-L481) [README.md145-227](https://github.com/stable-net/go-stablenet/blob/422cf168/README.md#L145-L227)

* * *

### Initialize the Node

Initialize the node database with the genesis block:

```
./build/bin/gstable init path/to/genesis.json
```

**Node Initialization Flow**

Yes

No

gstable init

initCommand()  
cmd/gstable/chaincmd.go

utils.MakeDataDir(ctx)

stack.OpenDatabaseWithFreezer('chaindata')

Load genesis.json

genesis.UnmarshalJSON()

core.SetupGenesisBlock(db, triedb, genesis)

genesis.Config.AnzeonEnabled()?

CheckValidity()  
Verify validators, BLS keys

genesis.ToBlock()

wbft.CreateInitialExtraData()  
Encode validators in header.Extra

core.InjectContracts()

Deploy NativeCoinAdapter  
0x0000...1000

Deploy GovValidator  
0x0000...1001

Deploy GovMasterMinter  
0x0000...1002

Deploy GovMinter  
0x0000...1003

Deploy GovCouncil  
0x0000...1004

genesis.Commit(db, triedb)

flushAlloc()  
Persist state to trie

WriteBlockAndSetHead()  
Write genesis block

Initialization Complete

The initialization process at [core/genesis.go232-280](https://github.com/stable-net/go-stablenet/blob/422cf168/core/genesis.go#L232-L280):

1.  Creates data directory via [cmd/utils/flags.go953-971](https://github.com/stable-net/go-stablenet/blob/422cf168/cmd/utils/flags.go#L953-L971) `MakeDataDir()` (default: `~/.ethereum` or `--datadir`)
2.  Opens `chaindata` database via [eth/backend.go134-137](https://github.com/stable-net/go-stablenet/blob/422cf168/eth/backend.go#L134-L137)
3.  If Anzeon is enabled, validates configuration via [core/genesis.go262-275](https://github.com/stable-net/go-stablenet/blob/422cf168/core/genesis.go#L262-L275)
4.  Encodes validators in `header.Extra` via `wbft.CreateInitialExtraData()`
5.  Deploys system contracts at genesis via [core/genesis.go271-274](https://github.com/stable-net/go-stablenet/blob/422cf168/core/genesis.go#L271-L274) `InjectContracts()`
6.  Commits state to database via [core/genesis.go153-186](https://github.com/stable-net/go-stablenet/blob/422cf168/core/genesis.go#L153-L186) `flushAlloc()`
7.  Writes genesis block via `blockchain.WriteBlockAndSetHead()`

Sources: [core/genesis.go232-280](https://github.com/stable-net/go-stablenet/blob/422cf168/core/genesis.go#L232-L280) [core/genesis.go262-275](https://github.com/stable-net/go-stablenet/blob/422cf168/core/genesis.go#L262-L275) [core/genesis.go153-186](https://github.com/stable-net/go-stablenet/blob/422cf168/core/genesis.go#L153-L186) [cmd/utils/flags.go953-971](https://github.com/stable-net/go-stablenet/blob/422cf168/cmd/utils/flags.go#L953-L971) [eth/backend.go134-137](https://github.com/stable-net/go-stablenet/blob/422cf168/eth/backend.go#L134-L137)

* * *

## Running a Node

### Basic Startup

Start a full node with default settings:

```
./build/bin/gstable
```

This starts the node with defaults from [eth/ethconfig/config.go57-94](https://github.com/stable-net/go-stablenet/blob/422cf168/eth/ethconfig/config.go#L57-L94):

-   Full sync mode (`SyncMode: downloader.FullSync`)
-   IPC RPC enabled at `~/.ethereum/gstable.ipc`
-   P2P listening on port `30303` ([cmd/utils/flags.go720-725](https://github.com/stable-net/go-stablenet/blob/422cf168/cmd/utils/flags.go#L720-L725))
-   Connection to bootnodes from [params/bootnodes.go21-35](https://github.com/stable-net/go-stablenet/blob/422cf168/params/bootnodes.go#L21-L35)

**Node Startup Flow**

Anzeon

Clique

Ethash

main()  
cmd/gstable/main.go

gstable command

defaultNodeConfig()  
Get node.DefaultConfig

makeConfigNode(ctx)  
Apply CLI flags

setNodeConfig(ctx, cfg)

DataDir from --datadir  
default: ~/.ethereum

P2P from --port, --maxpeers  
\--bootnodes, --nodiscover

RPC from --http, --ws, --ipc

makeFullNode(ctx)

stack = node.New(config)

RegisterEthService(stack, cfg)

eth.New(stack, ethConfig)

stack.OpenDatabaseWithFreezer('chaindata')

core.LoadChainConfig(chainDb)

ethconfig.CreateConsensusEngine()

wbftBackend.New(chainConfig, nodekey)

clique.New()

ethash.New()

core.NewBlockChain(db, engine)

txpool.New(config, blockchain)

miner.New(eth, config, engine)

stack.Start()

p2pServer.Start()  
Listen on --port

StartRPC()  
IPC, HTTP, WS servers

ethereum.Start()

handler.Start(maxPeers)  
Begin chain sync

If --mine: miner.Start()

The startup process at [eth/backend.go110-303](https://github.com/stable-net/go-stablenet/blob/422cf168/eth/backend.go#L110-L303):

1.  Loads configuration via [cmd/gstable/config.go](https://github.com/stable-net/go-stablenet/blob/422cf168/cmd/gstable/config.go) applying flags from [cmd/utils/flags.go88-929](https://github.com/stable-net/go-stablenet/blob/422cf168/cmd/utils/flags.go#L88-L929)
2.  Creates `node.Node` stack with P2P and RPC configuration
3.  Registers Ethereum service via [eth/backend.go110](https://github.com/stable-net/go-stablenet/blob/422cf168/eth/backend.go#L110-L110) `eth.New()`
4.  Opens database at [eth/backend.go134](https://github.com/stable-net/go-stablenet/blob/422cf168/eth/backend.go#L134-L134) via `stack.OpenDatabaseWithFreezer("chaindata")`
5.  Loads chain config at [eth/backend.go149](https://github.com/stable-net/go-stablenet/blob/422cf168/eth/backend.go#L149-L149) via `core.LoadChainConfig()`
6.  Creates consensus engine at [eth/ethconfig/config.go97-161](https://github.com/stable-net/go-stablenet/blob/422cf168/eth/ethconfig/config.go#L97-L161) based on chain config
7.  Initializes blockchain at [eth/backend.go225](https://github.com/stable-net/go-stablenet/blob/422cf168/eth/backend.go#L225-L225) via `core.NewBlockChain()`
8.  Creates transaction pool at [eth/backend.go241](https://github.com/stable-net/go-stablenet/blob/422cf168/eth/backend.go#L241-L241) via `txpool.New()`
9.  Creates miner at [eth/backend.go264](https://github.com/stable-net/go-stablenet/blob/422cf168/eth/backend.go#L264-L264) via `miner.New()`
10.  Starts services at [eth/backend.go526-545](https://github.com/stable-net/go-stablenet/blob/422cf168/eth/backend.go#L526-L545) including P2P, RPC, and chain synchronization

Sources: [eth/backend.go110-303](https://github.com/stable-net/go-stablenet/blob/422cf168/eth/backend.go#L110-L303) [eth/backend.go526-545](https://github.com/stable-net/go-stablenet/blob/422cf168/eth/backend.go#L526-L545) [eth/ethconfig/config.go57-94](https://github.com/stable-net/go-stablenet/blob/422cf168/eth/ethconfig/config.go#L57-L94) [cmd/utils/flags.go88-929](https://github.com/stable-net/go-stablenet/blob/422cf168/cmd/utils/flags.go#L88-L929) [params/bootnodes.go21-35](https://github.com/stable-net/go-stablenet/blob/422cf168/params/bootnodes.go#L21-L35)

* * *

### Running with RPC

Enable HTTP RPC for remote access:

```
./build/bin/gstable \
  --http \
  --http.addr 0.0.0.0 \
  --http.port 8545 \
  --http.api eth,net,web3
```

**RPC Configuration Flags**

| Flag | Purpose | Default | Source |
| --- | --- | --- | --- |
| --http | Enable HTTP-RPC server | false | cmd/utils/flags.go581-585 |
| --http.addr | Listening interface | localhost | cmd/utils/flags.go586-591 |
| --http.port | HTTP port | 8545 | cmd/utils/flags.go592-597 |
| --http.api | Enabled API namespaces | "" (none) | cmd/utils/flags.go610-615 |
| --http.corsdomain | CORS domains | "" | cmd/utils/flags.go598-603 |
| --http.vhosts | Virtual hostnames | localhost | cmd/utils/flags.go604-609 |
| --ws | Enable WebSocket-RPC server | false | cmd/utils/flags.go639-643 |
| --ws.port | WebSocket port | 8546 | cmd/utils/flags.go650-655 |

Available API namespaces (defined in [eth/backend.go324-352](https://github.com/stable-net/go-stablenet/blob/422cf168/eth/backend.go#L324-L352)):

-   `eth` - Ethereum blockchain APIs ([internal/ethapi/api.go](https://github.com/stable-net/go-stablenet/blob/422cf168/internal/ethapi/api.go))
-   `net` - Network status APIs
-   `web3` - Web3 utility APIs
-   `txpool` - Transaction pool inspection
-   `admin` - Node administration
-   `debug` - Debugging and profiling
-   `miner` - Mining control (validator operations)

Sources: [cmd/utils/flags.go581-673](https://github.com/stable-net/go-stablenet/blob/422cf168/cmd/utils/flags.go#L581-L673) [eth/backend.go324-352](https://github.com/stable-net/go-stablenet/blob/422cf168/eth/backend.go#L324-L352)

* * *

### Running a Validator

To participate in consensus as a validator:

1.  Ensure your validator key is registered in `GovValidator` contract at `0x0000...1001`
2.  Generate a BLS key from your nodekey via `bls.DeriveFromECDSA()`
3.  Start with mining enabled:

```
./build/bin/gstable \
  --nodekey /path/to/nodekey \
  --mine \
  --miner.etherbase 0xYourValidatorAddress
```

**Validator Startup Process**

false

Clique

WBFT

Valid

Invalid

Yes

No

eth.StartMining()

miner.isRunning()?

miner.GetGasTip()  
Read from GovValidator

txPool.SetGasTip(price)  
Update priority threshold

eth.Etherbase()  
\--miner.etherbase flag

engine type?

clique.Authorize(etherbase)  
Sign with account

wbftBackend.Start()

LoadValidators()  
Read GovValidator contract

Verify BLS key  
derived from nodekey

worker.start()

Error: not authorized validator

newWorkLoopWBFT()  
Listen for consensus events

<-chainHeadCh  
New block imported

engine.NewChainHead()  
Signal ready for round

Am I proposer for round?

commitWork()  
Assemble block

Wait for Prepare msgs

commitTransactions()  
Select from txpool

engine.Finalize()  
Calculate rewards

engine.Seal()  
WBFT consensus

Broadcast Prepare  
with block hash + BLS sig

Collect 2f+1 Prepares  
from other validators

Broadcast Commit  
with aggregated Prepare sigs

Collect 2f+1 Commits

blockchain.InsertChain()  
Add to canonical chain

The WBFT engine startup at [miner/worker.go447-450](https://github.com/stable-net/go-stablenet/blob/422cf168/miner/worker.go#L447-L450):

1.  Calls `wbftBackend.Start()` which loads validators from [consensus/wbft/backend/backend.go](https://github.com/stable-net/go-stablenet/blob/422cf168/consensus/wbft/backend/backend.go)
2.  Verifies BLS key matches registered validator at [consensus/wbft/backend/backend.go](https://github.com/stable-net/go-stablenet/blob/422cf168/consensus/wbft/backend/backend.go)
3.  Participates in consensus via Prepare/Commit phases at [consensus/wbft/core/handler.go](https://github.com/stable-net/go-stablenet/blob/422cf168/consensus/wbft/core/handler.go)
4.  Proposes blocks when selected by round-robin at [consensus/wbft/core/core.go](https://github.com/stable-net/go-stablenet/blob/422cf168/consensus/wbft/core/core.go)

Mining configuration flags from [cmd/utils/flags.go434-472](https://github.com/stable-net/go-stablenet/blob/422cf168/cmd/utils/flags.go#L434-L472):

-   `--mine` - Enable mining/validation ([cmd/utils/flags.go434-438](https://github.com/stable-net/go-stablenet/blob/422cf168/cmd/utils/flags.go#L434-L438))
-   `--miner.etherbase` - Block reward recipient address ([cmd/utils/flags.go451-455](https://github.com/stable-net/go-stablenet/blob/422cf168/cmd/utils/flags.go#L451-L455))
-   `--miner.gaslimit` - Target gas ceiling ([cmd/utils/flags.go439-444](https://github.com/stable-net/go-stablenet/blob/422cf168/cmd/utils/flags.go#L439-L444))

For detailed validator operations, see [Validator Operations](/stable-net/go-stablenet/11.2-validator-operations).

Sources: [eth/backend.go435-471](https://github.com/stable-net/go-stablenet/blob/422cf168/eth/backend.go#L435-L471) [miner/worker.go447-450](https://github.com/stable-net/go-stablenet/blob/422cf168/miner/worker.go#L447-L450) [cmd/utils/flags.go434-472](https://github.com/stable-net/go-stablenet/blob/422cf168/cmd/utils/flags.go#L434-L472)

* * *

## Configuration Management

### Using Configuration Files

Instead of CLI flags, use a TOML configuration file:

```
./build/bin/gstable --config config.toml
```

Generate a configuration template:

```
./build/bin/gstable dumpconfig > config.toml
```

Example minimal configuration:

```
[Eth]
NetworkId = 1111
SyncMode = "snap"

[Node]
DataDir = "/var/lib/gstable"
HTTPHost = "0.0.0.0"
HTTPPort = 8545

[Node.P2P]
MaxPeers = 50
NoDiscovery = false
StaticNodes = [
  "enode://abcd...@192.168.1.100:30303"
]
```

Sources: [README.md307-323](https://github.com/stable-net/go-stablenet/blob/422cf168/README.md#L307-L323)

* * *

## Verifying Installation

Check the node is running correctly:

```
# Check version
./build/bin/gstable version

# Attach to running node
./build/bin/gstable attach ~/.ethereum/gstable.ipc

# In console, check sync status
> eth.syncing

# Check validator status (if mining)
> eth.mining
> eth.coinbase
```

Sources: [README.md293-306](https://github.com/stable-net/go-stablenet/blob/422cf168/README.md#L293-L306)

* * *

## Next Steps

Now that you have a running node, explore the following topics:

-   **[Installation and Building](/stable-net/go-stablenet/2.1-installation-and-building)** - Deep dive into build system, cross-compilation, CI/CD pipeline
-   **[Node Configuration](/stable-net/go-stablenet/2.2-node-configuration)** - Comprehensive guide to all configuration flags and options
-   **[Genesis Setup](/stable-net/go-stablenet/2.3-genesis-setup-and-network-types)** - Advanced genesis configuration for different network types
-   **[WBFT Consensus Protocol](/stable-net/go-stablenet/4.1-anzeon-wbft-consensus-protocol)** - Understanding the Anzeon consensus mechanism
-   **[Validator Operations](/stable-net/go-stablenet/11.3-node-monitoring-and-maintenance)** - Running a validator node in production

* * *

## Common Issues

### Build Failures

If compilation fails with C compiler errors:

-   Ensure gcc/clang is installed: `gcc --version`
-   On macOS, install Xcode Command Line Tools: `xcode-select --install`
-   On Windows, use MSYS2 MinGW toolchain

### Genesis Initialization Errors

If `gstable init` fails:

-   Verify `genesis.json` is valid JSON
-   Check `anzeon.init.validators` array is not empty
-   Ensure BLS keys are 48-byte hex strings (96 characters + `0x` prefix)

### Node Won't Start

If the node fails to start:

-   Check data directory permissions
-   Verify port 30303 is not in use: `netstat -an | grep 30303`
-   Review logs for error messages

Sources: [README.md229-244](https://github.com/stable-net/go-stablenet/blob/422cf168/README.md#L229-L244) [build/ci.go192-246](https://github.com/stable-net/go-stablenet/blob/422cf168/build/ci.go#L192-L246)

This wiki is featured in the [repository](https://github.com/stable-net/go-stablenet/blob/dev/README.md)

Dismiss

Refresh this wiki

This wiki was recently refreshed. Please wait 3 days to refresh again.

### On this page

-   [Getting Started](#getting-started)
-   [Overview](#overview)
-   [Prerequisites](#prerequisites)
-   [Required Dependencies](#required-dependencies)
-   [Build Process](#build-process)
-   [Building from Source](#building-from-source)
-   [Docker Build](#docker-build)
-   [Executables Overview](#executables-overview)
-   [Node Initialization](#node-initialization)
-   [Generating a Genesis File](#generating-a-genesis-file)
-   [Manual Genesis Configuration](#manual-genesis-configuration)
-   [Initialize the Node](#initialize-the-node)
-   [Running a Node](#running-a-node)
-   [Basic Startup](#basic-startup)
-   [Running with RPC](#running-with-rpc)
-   [Running a Validator](#running-a-validator)
-   [Configuration Management](#configuration-management)
-   [Using Configuration Files](#using-configuration-files)
-   [Verifying Installation](#verifying-installation)
-   [Next Steps](#next-steps)
-   [Common Issues](#common-issues)
-   [Build Failures](#build-failures)
-   [Genesis Initialization Errors](#genesis-initialization-errors)
-   [Node Won't Start](#node-wont-start)

Ask Devin about stable-net/go-stablenet

Fast