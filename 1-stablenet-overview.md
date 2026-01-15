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

# StableNet Overview

Relevant source files

-   [README.md](https://github.com/stable-net/go-stablenet/blob/422cf168/README.md)
-   [cmd/genesis\_generator/genesis\_generator.go](https://github.com/stable-net/go-stablenet/blob/422cf168/cmd/genesis_generator/genesis_generator.go)
-   [cmd/genesis\_generator/reader.go](https://github.com/stable-net/go-stablenet/blob/422cf168/cmd/genesis_generator/reader.go)
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
-   [miner/miner.go](https://github.com/stable-net/go-stablenet/blob/422cf168/miner/miner.go)
-   [miner/miner\_test.go](https://github.com/stable-net/go-stablenet/blob/422cf168/miner/miner_test.go)
-   [miner/worker.go](https://github.com/stable-net/go-stablenet/blob/422cf168/miner/worker.go)
-   [miner/worker\_test.go](https://github.com/stable-net/go-stablenet/blob/422cf168/miner/worker_test.go)
-   [params/bootnodes.go](https://github.com/stable-net/go-stablenet/blob/422cf168/params/bootnodes.go)
-   [params/config.go](https://github.com/stable-net/go-stablenet/blob/422cf168/params/config.go)
-   [systemcontracts/coin\_adapter.go](https://github.com/stable-net/go-stablenet/blob/422cf168/systemcontracts/coin_adapter.go)

**Purpose**: This document provides a high-level introduction to the StableNet blockchain, its unique stablecoin-focused architecture, key differences from standard Ethereum, and the role of the WBFT consensus mechanism and governance system.

**Scope**: This overview covers the fundamental design principles, architecture, and differentiating features of StableNet. For detailed implementation guides, see:

-   Node setup and configuration: [Getting Started](/stable-net/go-stablenet/2-getting-started)
-   WBFT consensus internals: [WBFT Consensus Protocol](/stable-net/go-stablenet/4.1-anzeon-wbft-consensus-protocol)
-   Governance contract details: [System Contracts Overview](/stable-net/go-stablenet/5.1-system-contracts-overview)
-   Gas fee mechanics: [Gas Fee Policy](/stable-net/go-stablenet/6.4-gas-fee-policy)

* * *

## What is StableNet?

StableNet is a blockchain protocol designed specifically for stablecoin operations, forked from the WBFT (WEMIX Byzantine Fault Tolerance) implementation. It maintains full EVM compatibility while introducing fundamental changes to support stablecoins as the native base coin used for gas payments.

**Core Innovation**: Unlike traditional blockchains where the base coin is pre-minted and subject to speculative value fluctuation, StableNet implements a **1:1 fiat-pegged base coin** with dynamic minting and burning controlled by a decentralized oracle system of minters who verify real-world fiat deposits and withdrawals.

**Key Characteristics**:

-   **Proof-of-Authority (PoA)** consensus using Anzeon WBFT engine
→ **Proof-of-Authority (PoA)** validator architecture
- **Byzantine Fault Tolerance (BFT)** consensus using Anzeon WBFT engine

-   **Zero inflation** - no block rewards for validators
-   **Governance-controlled** priority fees (gasTip)
-   **Base fees paid to validators** (not burned)
-   **ERC20-compatible native coin** via NativeCoinAdapter system contract

Sources: [README.md1-17](https://github.com/stable-net/go-stablenet/blob/422cf168/README.md#L1-L17) [params/config.go44-143](https://github.com/stable-net/go-stablenet/blob/422cf168/params/config.go#L44-L143)

* * *

## Architectural Differences from Ethereum

The following table summarizes StableNet's key divergences from standard Ethereum:

| Aspect | Ethereum | StableNet |
| --- | --- | --- |
| Consensus | PoS (Beacon Chain) | PoA with WBFT (Anzeon) |
| Base Coin | ETH (pre-minted) | Stablecoin (1:1 fiat peg) |
| Coin Supply | Fixed + staking rewards | Dynamic mint/burn by minters |
| Block Rewards | Yes (staking) | No - validators earn only fees |
| Base Fee | Burned (EIP-1559) | Paid to validators |
| Priority Fee | User-set (maxPriorityFeePerGas) | Governance-set (gasTip) |
| Base Fee Adjustment | Starts at 50% block capacity | Starts at 90% block capacity |
| Native Coin ERC20 | Requires wrapper contracts | Built-in NativeCoinAdapter |
| Block Time | ~12 seconds | ~1 second (configurable) |
| Epoch Length | ~6.4 minutes | 10 blocks (configurable) |

Sources: [README.md18-112](https://github.com/stable-net/go-stablenet/blob/422cf168/README.md#L18-L112) [params/protocol\_params.go116-121](https://github.com/stable-net/go-stablenet/blob/422cf168/params/protocol_params.go#L116-L121)

* * *

## System Architecture Overview

### High-Level Component Diagram

System Contracts

Storage

Chain State

Block Production

Consensus Layer

Ethereum Protocol Service

Node Management

User Interface Layer

reads

reads gasTip

executes

cmd/geth/main.go  
geth() entrypoint

cmd/utils/flags.go  
MakeDataDir()  
SetupGenesisBlock()

node.Node  
stack.Server()  
stack.RegisterAPIs()

node.Config  
DataDir, P2P, RPC

eth.Ethereum  
type Ethereum struct

eth.New()  
initializes all subsystems

EthAPIBackend  
implements Backend interface

consensus.Engine interface

wbft/backend.Backend  
Start(), Seal()

wbft/core.Core  
consensus state machine

miner.Miner  
New(), Start()

miner.worker  
mainLoop(), commitWork()

environment struct  
state, header, txs, receipts

core.BlockChain  
InsertChain(), StateAt()

txpool.TxPool  
Add(), Pending()

state.StateDB  
Commit(), GetBalance()

vm.EVM  
Call(), Create()

ethdb.Database  
chainDb (LevelDB/Pebble)

triedb.Database  
trie node storage

systemcontracts.GovValidator  
0x1001

systemcontracts.NativeCoinAdapter  
0x1000

**Code Entity Mapping**: The `eth.Ethereum` struct at [eth/backend.go70-106](https://github.com/stable-net/go-stablenet/blob/422cf168/eth/backend.go#L70-L106) contains fields `config`, `txPool`, `blockchain`, `engine`, `miner` which directly correspond to the components shown. The `eth.New()` function [eth/backend.go110-303](https://github.com/stable-net/go-stablenet/blob/422cf168/eth/backend.go#L110-L303) performs initialization in this order: database → genesis → consensus engine → blockchain → txpool → miner.

Sources: [eth/backend.go70-106](https://github.com/stable-net/go-stablenet/blob/422cf168/eth/backend.go#L70-L106) [eth/backend.go110-303](https://github.com/stable-net/go-stablenet/blob/422cf168/eth/backend.go#L110-L303) [miner/worker.go187-258](https://github.com/stable-net/go-stablenet/blob/422cf168/miner/worker.go#L187-L258) [miner/miner.go86-111](https://github.com/stable-net/go-stablenet/blob/422cf168/miner/miner.go#L86-L111)

* * *

## Node Initialization Flow

### Startup Sequence Diagram

"eth.Start()""miner.New()""core.NewBlockChain()""ethconfig.CreateConsensusEngine()""core.InjectContracts()""core.SetupGenesisBlock()""eth.New()""node.NodeNew()""cmd/utils/flags.goMakeDataDir()""cmd/geth/main.gogeth()""eth.Start()""miner.New()""core.NewBlockChain()""ethconfig.CreateConsensusEngine()""core.InjectContracts()""core.SetupGenesisBlock()""eth.New()""node.NodeNew()""cmd/utils/flags.goMakeDataDir()""cmd/geth/main.gogeth()"Initializes DataDir,P2P, RPC serversDeploy contracts at0x1000-0x1004alt\[First run (no genesis in db)\]Returns wbft.Backendfor Anzeon chainswbftEngine.Start()Begins consensusctx.String(DataDirFlag.Name)MakeDataDir() returns pathnode.New(nodeConfig)eth.New(stack, ethConfig)stack.OpenDatabaseWithFreezer("chaindata")SetupGenesisBlock(chainDb, triedb, genesis)Check config.AnzeonInjectContracts(genesis, config)genesis.Commit(db, triedb)CreateConsensusEngine(chainConfig, nodeKey, chainDb)core.NewBlockChain(chainDb, cacheConfig, genesis, engine)txpool.New() with legacypoolminer.New(eth, minerConfig, chainConfig, engine)stack.Start()eth.Start()

**Key Functions Called**:

-   `MakeDataDir()` at [cmd/utils/flags.go956-971](https://github.com/stable-net/go-stablenet/blob/422cf168/cmd/utils/flags.go#L956-L971) determines the data directory path
-   `eth.New()` at [eth/backend.go110-303](https://github.com/stable-net/go-stablenet/blob/422cf168/eth/backend.go#L110-L303) orchestrates initialization:
    -   Line 134: Opens chaindata database with `stack.OpenDatabaseWithFreezer()`
    -   Line 149: Loads chain config with `core.LoadChainConfig()`
    -   Line 154: Creates consensus engine with `ethconfig.CreateConsensusEngine()`
    -   Line 225: Creates blockchain with `core.NewBlockChain()`
    -   Line 264: Creates miner with `miner.New()`
-   `SetupGenesisBlock()` at [core/genesis.go232-379](https://github.com/stable-net/go-stablenet/blob/422cf168/core/genesis.go#L232-L379) handles genesis initialization
    -   Line 271: Calls `InjectContracts()` if Anzeon is enabled
-   `InjectContracts()` at [core/genesis.go271-274](https://github.com/stable-net/go-stablenet/blob/422cf168/core/genesis.go#L271-L274) deploys system contracts

Sources: [cmd/utils/flags.go956-971](https://github.com/stable-net/go-stablenet/blob/422cf168/cmd/utils/flags.go#L956-L971) [eth/backend.go110-303](https://github.com/stable-net/go-stablenet/blob/422cf168/eth/backend.go#L110-L303) [core/genesis.go232-379](https://github.com/stable-net/go-stablenet/blob/422cf168/core/genesis.go#L232-L379) [core/genesis.go261-275](https://github.com/stable-net/go-stablenet/blob/422cf168/core/genesis.go#L261-L275)

* * *

## Stablecoin Economics Model

StableNet's economic model fundamentally differs from traditional blockchains by maintaining a **1:1 peg with fiat currency** and implementing **zero inflation**.

### Key Economic Principles

1.  **No Pre-Mining**: Only minimal funds required for chain operation are pre-issued at genesis
2.  **Dynamic Supply**: Minters can issue and burn tokens throughout operation
3.  **Oracle-Verified**: Minters verify fiat deposits/withdrawals in traditional banking systems
4.  **Inflation-Free**: No block rewards; validator revenue comes solely from transaction fees
5.  **Auditable Supply**: Total supply changes only through mint/burn operations tracked on-chain

### Fee Distribution Model

Distribution

Fee Collection

Transaction Fee Components

100% paid to

Base Fee  
(dynamic, protocol-set)

Priority Fee (gasTip)  
(fixed, governance-set)

Total Transaction Fee  
gasUsed \* (baseFee + gasTip)

Block Validator  
(coinbase address)

No burning  
No block rewards  
Supply constant

**Base Fee Adjustment**: The base fee increases only when block gas usage exceeds 90% capacity (vs. 50% in Ethereum). This is implemented through the `GasTargetPercentage` constant set to 90 in protocol parameters. The adjustment logic uses `BaseFeeChangeRate` of 15 to control the rate of increase/decrease.

**Gas Tip Governance**: Unlike Ethereum where miners/validators set their own minimum, StableNet's `gasTip` (priority fee) is stored in the GovValidator contract and read by the worker during block production. The worker function `updateGasTipFromContract()` at [miner/worker.go313-324](https://github.com/stable-net/go-stablenet/blob/422cf168/miner/worker.go#L313-L324) reads this value from contract state and propagates it to the transaction pool via `setGasTipUnsafe()` at [miner/worker.go377-390](https://github.com/stable-net/go-stablenet/blob/422cf168/miner/worker.go#L377-L390)

Sources: [README.md106-125](https://github.com/stable-net/go-stablenet/blob/422cf168/README.md#L106-L125) [miner/worker.go313-324](https://github.com/stable-net/go-stablenet/blob/422cf168/miner/worker.go#L313-L324) [miner/worker.go377-390](https://github.com/stable-net/go-stablenet/blob/422cf168/miner/worker.go#L377-L390) [params/config.go78-89](https://github.com/stable-net/go-stablenet/blob/422cf168/params/config.go#L78-L89)

* * *

## Anzeon WBFT Consensus

Anzeon is StableNet's specialized adaptation of the WBFT (WEMIX Byzantine Fault Tolerance) consensus engine, optimized for PoA stablecoin networks.

### WBFT Configuration

The consensus engine is configured through the `anzeon` section in chain config [params/config.go65-142](https://github.com/stable-net/go-stablenet/blob/422cf168/params/config.go#L65-L142):

| Parameter | Description | Default |
| --- | --- | --- |
| epochLength | Blocks per epoch | 10 |
| blockPeriodSeconds | Target block time | 1 second |
| requestTimeoutSeconds | Consensus round timeout | 2 seconds |
| proposerPolicy | Block proposer selection | 0 (round-robin) |

### Validator Structure

Each validator consists of three cryptographic keys [README.md48](https://github.com/stable-net/go-stablenet/blob/422cf168/README.md#L48-L48):

Single Validator Entity

Operator Key (EOA/Multisig)  
Governance voting  
Validator management

Validator Key (ECDSA)  
Block signing  
Coinbase address

BLS Public Key  
Consensus message signing  
Signature aggregation

Example from config:  
members: 0xaa5f...4697  
validators: 0xaa5f...4697  
blsPublicKeys: 0xaec4...8b9b

Configuration example from mainnet config [params/config.go80-88](https://github.com/stable-net/go-stablenet/blob/422cf168/params/config.go#L80-L88):

-   `members`: Operator wallet addresses used for governance voting
-   `validators`: Validator key addresses used as block coinbase
-   `blsPublicKeys`: BLS public keys (96 bytes hex-encoded) for consensus message signing
-   `gasTip`: Initial priority fee value (e.g., "5000000000000" = 5 Gwei)

These values are parsed during genesis setup and stored in the GovValidator contract storage at address 0x1001.

### Epoch-Based Validator Selection

Block 1-10

Block 11+

Genesis

anzeon.init.validators

First epoch

InitValidators

ConsensusActive

Epoch2

GovValidator.getValidators()

Every 10 blocks

ContractValidators

EpochTransition

Validators specified in  
genesis anzeon.init config

Validators from GovValidator  
contract at 0x1001

The first epoch (blocks 1-10) uses validators specified in `anzeon.init` [params/config.go72-75](https://github.com/stable-net/go-stablenet/blob/422cf168/params/config.go#L72-L75) Subsequent epochs query the GovValidator contract [params/config.go77-89](https://github.com/stable-net/go-stablenet/blob/422cf168/params/config.go#L77-L89) for the active validator set.

Sources: [params/config.go65-142](https://github.com/stable-net/go-stablenet/blob/422cf168/params/config.go#L65-L142) [README.md123-227](https://github.com/stable-net/go-stablenet/blob/422cf168/README.md#L123-L227) [eth/ethconfig/config.go213-268](https://github.com/stable-net/go-stablenet/blob/422cf168/eth/ethconfig/config.go#L213-L268)

* * *

## Governance System

StableNet implements on-chain governance through five system contracts deployed at genesis at predetermined addresses.

### System Contracts Architecture

On-Chain State

Coin Supply Governance

Validator Governance (0x1001)

manages

sets

registers

configures

mints/burns via

modifies

General Governance (0x1004)

GovCouncil  
Future governance functions

GovValidator  
Manages validator set  
Controls gasTip parameter

GovMasterMinter (0x1002)  
Registers/removes minters  
Sets minter allowances

GovMinter (0x1003)  
Mint/burn approval votes  
Multi-sig oracle for fiat

NativeCoinAdapter (0x1000)  
ERC20 interface for base coin  
Manages native balances

Active Validators  
BLS Keys  
Operator Keys

Total Supply  
Minter Allowances  
Account Balances

gasTip (priority fee)

### Contract Addresses and Initialization

All governance contracts are deployed at genesis with immutable addresses defined in [params/anzeon\_contracts.go](https://github.com/stable-net/go-stablenet/blob/422cf168/params/anzeon_contracts.go):

-   **NativeCoinAdapter**: `0x0000000000000000000000000000000000001000`
-   **GovValidator**: `0x0000000000000000000000000000000000001001`
-   **GovMasterMinter**: `0x0000000000000000000000000000000000001002`
-   **GovMinter**: `0x0000000000000000000000000000000000001003`
-   **GovCouncil**: `0x0000000000000000000000000000000000001004`

These contracts are injected during genesis block creation [core/genesis.go271-274](https://github.com/stable-net/go-stablenet/blob/422cf168/core/genesis.go#L271-L274) via `InjectContracts()` using parameters from the chain config [params/config.go76-141](https://github.com/stable-net/go-stablenet/blob/422cf168/params/config.go#L76-L141)

Sources: [params/config.go76-141](https://github.com/stable-net/go-stablenet/blob/422cf168/params/config.go#L76-L141) [README.md39-61](https://github.com/stable-net/go-stablenet/blob/422cf168/README.md#L39-L61)

* * *

## NativeCoinAdapter: ERC20-Compatible Native Coin

The NativeCoinAdapter is StableNet's most distinctive feature, enabling the native base coin (used for gas) to be fully compatible with ERC20 token standards without requiring wrapper contracts.

### Design Principles

1.  **Direct Balance Mapping**: `balanceOf(address)` returns the account's actual native balance, not a separate token balance
2.  **Event Generation**: All native transfers (including gas payments) emit `Transfer` events
3.  **Precompile Integration**: Uses precompile code to enforce allowances and approvals
4.  **Exclusive Mint/Burn**: Only this contract can modify total supply
5.  **Full FiatTokenV2\_2 Compatibility**: Supports all methods from Circle's USDC implementation

### Architecture Diagram

Events

State Management

NativeCoinAdapter Contract (0x1000)

User Interactions

emits

emits

emits

emits

DApp / User

ERC20 Method Calls  
transfer() / approve() / balanceOf()

Native Coin Transfer  
(for gas fees)

ERC20 Methods  
FiatTokenV2\_2 Compatible

mint() / burn()  
Only by authorized minters

Contract Storage  
\_allowances mapping  
\_totalSupply

Precompile Code  
Enforces allowances  
Updates native balances

state.StateDB  
Account native balances

Transfer(from, to, value)

Approval(owner, spender, value)

Mint(minter, to, amount)

Burn(burner, amount)

### Key Implementation Details

**Initialization Parameters** [params/config.go91-103](https://github.com/stable-net/go-stablenet/blob/422cf168/params/config.go#L91-L103):

-   `name`: Token name (e.g., "KRC1")
-   `symbol`: Token symbol (e.g., "KRC1")
-   `decimals`: Decimal places (18)
-   `currency`: Underlying fiat currency (e.g., "KRW")
-   `masterMinter`: GovMasterMinter contract address (0x1002)
-   `minters`: Initial minter addresses (comma-separated)
-   `minterAllowed`: Maximum mint allowance per minter (e.g., 1e28)

**Contract Code Reference**: The NativeCoinAdapter implementation is injected at genesis via `InjectContracts()` which reads compiled bytecode and initializes storage slots. The contract address `0x1000` is defined as `DefaultNativeCoinAdapterAddress` in the params package.

Sources: [README.md89-105](https://github.com/stable-net/go-stablenet/blob/422cf168/README.md#L89-L105) [params/config.go91-103](https://github.com/stable-net/go-stablenet/blob/422cf168/params/config.go#L91-L103) [core/genesis.go261-275](https://github.com/stable-net/go-stablenet/blob/422cf168/core/genesis.go#L261-L275)

* * *

## Mint and Burn Protocol

The mint/burn protocol implements a multi-signature oracle system where minter members collectively verify and approve fiat-backed operations.

### Minting Workflow

"Beneficiary""NativeCoinAdapter0x1000""GovMinter Contract0x1003""Minter Member N""Minter Member 2""Minter Member 1""Traditional BankCollateral Account""Beneficiary""NativeCoinAdapter0x1000""GovMinter Contract0x1003""Minter Member N""Minter Member 2""Minter Member 1""Traditional BankCollateral Account"Proposal createdQuorum reached (2f+1 approvals)Deposit fiat (e.g., 1000 KRW)Detect depositCreate mint proof:\- deposit\_id\- amount (1000)\- beneficiary address\- timestampproposeMint(proof)Verify proof off-chainapproveMint(proposalId)Verify proof off-chainapproveMint(proposalId)mint(beneficiary, 1000)Increase totalSupply by 1000Credit 1000 native coinsEmit Mint event

### Burning Workflow

"Traditional Bank""NativeCoinAdapter""GovMinter Contract""Minter Member N""Minter Member 2""Minter Member 1""Token Holder""Traditional Bank""NativeCoinAdapter""GovMinter Contract""Minter Member N""Minter Member 2""Minter Member 1""Token Holder"Proposal createdQuorum reachedRequest burn + withdrawal(1000 native coins)Issue withdrawal\_idCreate burn proof:\- withdrawal\_id\- amount (1000)\- owner address\- timestampproposeBurn(proof)Verify proof off-chainapproveBurn(proposalId)Verify proof off-chainapproveBurn(proposalId)burn(owner, 1000)Decrease totalSupply by 1000Deduct 1000 native coinsEmit Burn eventTrigger fiat withdrawalTransfer 1000 KRW to user account

### Proof Requirements

**Mint Proof** [README.md66-75](https://github.com/stable-net/go-stablenet/blob/422cf168/README.md#L66-L75):

-   `deposit_id`: Unique identifier from bank
-   `amount`: Tokens to mint (matches fiat deposit)
-   `beneficiary`: Receiving address
-   `timestamp`: When deposit was detected

**Burn Proof** [README.md77-87](https://github.com/stable-net/go-stablenet/blob/422cf168/README.md#L77-L87):

-   `withdrawal_id`: Unique identifier for withdrawal
-   `amount`: Tokens to burn
-   `owner`: Address holding tokens
-   `timestamp`: When burn was requested

All minter members must verify these proofs off-chain before submitting approval votes on-chain. Once a quorum (typically 2f+1 where f is the maximum Byzantine faults) is reached, the operation executes automatically.

Sources: [README.md63-87](https://github.com/stable-net/go-stablenet/blob/422cf168/README.md#L63-L87) [params/config.go118-129](https://github.com/stable-net/go-stablenet/blob/422cf168/params/config.go#L118-L129)

* * *

## Key Code Entry Points

For developers exploring the codebase, these are the primary entry points for each major subsystem:

| Subsystem | Primary Files | Key Structs/Functions | Line References |
| --- | --- | --- | --- |
| Node Entry | cmd/geth/main.go | geth(), startNode() | Entry point |
| Configuration | cmd/utils/flags.go | MakeDataDir(), flag definitions | cmd/utils/flags.go90-929 |
| Ethereum Service | eth/backend.go | type Ethereum struct, New(), Start() | eth/backend.go70-106 eth/backend.go110-303 |
| Consensus Engine | eth/ethconfig/config.go | CreateConsensusEngine() | eth/ethconfig/config.go179-268 |
| Genesis Setup | core/genesis.go | SetupGenesisBlock(), InjectContracts() | core/genesis.go232-379 core/genesis.go261-275 |
| Block Production | miner/worker.go | type worker struct, mainLoop(), commitWork() | miner/worker.go187-332 miner/worker.go687-1157 |
| Miner Coordinator | miner/miner.go | type Miner struct, New(), Start() | miner/miner.go86-111 miner/miner.go181-192 |
| WBFT Backend | consensus/wbft/backend/backend.go | type Backend struct, Start(), Seal() | WBFT consensus implementation |
| Transaction Pool | core/txpool/txpool.go | type TxPool struct, Add(), Pending() | Transaction validation and queueing |
| State Management | core/state/statedb.go | type StateDB struct, Commit(), GetBalance() | Account state and journaling |
| Chain Config | params/config.go | ChainConfig, AnzeonConfig, SystemContracts | params/config.go44-238 |
| System Contracts | systemcontracts/ | Contract bytecode and init logic | Genesis contract deployment |

Sources: [eth/backend.go70-303](https://github.com/stable-net/go-stablenet/blob/422cf168/eth/backend.go#L70-L303) [miner/worker.go187-332](https://github.com/stable-net/go-stablenet/blob/422cf168/miner/worker.go#L187-L332) [miner/miner.go86-111](https://github.com/stable-net/go-stablenet/blob/422cf168/miner/miner.go#L86-L111) [core/genesis.go232-379](https://github.com/stable-net/go-stablenet/blob/422cf168/core/genesis.go#L232-L379) [params/config.go44-238](https://github.com/stable-net/go-stablenet/blob/422cf168/params/config.go#L44-L238)

* * *

## Next Steps

To dive deeper into specific aspects of StableNet:

-   **Running a node**: See [Getting Started](/stable-net/go-stablenet/2-getting-started) for installation and configuration
-   **Understanding consensus**: See [WBFT Consensus Protocol](/stable-net/go-stablenet/4.1-anzeon-wbft-consensus-protocol) for Anzeon details
-   **Smart contract interaction**: See [NativeCoinAdapter](/stable-net/go-stablenet/5.2-nativecoinadapter-contract) for ERC20 compatibility
-   **Operating a validator**: See [Validator Operations](/stable-net/go-stablenet/11.3-node-monitoring-and-maintenance) for production deployment
-   **Transaction processing**: See [Transaction Lifecycle](/stable-net/go-stablenet/6.1-transaction-lifecycle) for execution flow
-   **Network synchronization**: See [Chain Synchronization](/stable-net/go-stablenet/7.3-chain-synchronization) for sync modes

This wiki is featured in the [repository](https://github.com/stable-net/go-stablenet/blob/dev/README.md)

Dismiss

Refresh this wiki

This wiki was recently refreshed. Please wait 3 days to refresh again.

### On this page

-   [StableNet Overview](#stablenet-overview)
-   [What is StableNet?](#what-is-stablenet)
-   [Architectural Differences from Ethereum](#architectural-differences-from-ethereum)
-   [System Architecture Overview](#system-architecture-overview)
-   [High-Level Component Diagram](#high-level-component-diagram)
-   [Node Initialization Flow](#node-initialization-flow)
-   [Startup Sequence Diagram](#startup-sequence-diagram)
-   [Stablecoin Economics Model](#stablecoin-economics-model)
-   [Key Economic Principles](#key-economic-principles)
-   [Fee Distribution Model](#fee-distribution-model)
-   [Anzeon WBFT Consensus](#anzeon-wbft-consensus)
-   [WBFT Configuration](#wbft-configuration)
-   [Validator Structure](#validator-structure)
-   [Epoch-Based Validator Selection](#epoch-based-validator-selection)
-   [Governance System](#governance-system)
-   [System Contracts Architecture](#system-contracts-architecture)
-   [Contract Addresses and Initialization](#contract-addresses-and-initialization)
-   [NativeCoinAdapter: ERC20-Compatible Native Coin](#nativecoinadapter-erc20-compatible-native-coin)
-   [Design Principles](#design-principles)
-   [Architecture Diagram](#architecture-diagram)
-   [Key Implementation Details](#key-implementation-details)
-   [Mint and Burn Protocol](#mint-and-burn-protocol)
-   [Minting Workflow](#minting-workflow)
-   [Burning Workflow](#burning-workflow)
-   [Proof Requirements](#proof-requirements)
-   [Key Code Entry Points](#key-code-entry-points)
-   [Next Steps](#next-steps)

Ask Devin about stable-net/go-stablenet

Fast