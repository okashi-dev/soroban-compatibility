# Support for Soroban Types

There are two distinct types of environments for contracts on Okashi - the *simulated environment* which executes contracts in the browser, and the *network environment* which executes contracts on Futurenet or Testnet.

## Simulated Environment

| Read | Write | Type | Comment |
| --- | --- | --- | --- |
| 🟨 | ✅ | `scSpecTypeVal` | Working on it. |
| ✅ | ✅ | `scSpecTypeBool` ||
| 🟥 | ✅ | `scSpecTypeVoid` | I reported a bug related to how `()` is encoded |
| 🟥 | ✅ | `scSpecTypeError` | This is because of a bug potentially, needs more research. |
| ✅ | ✅ | `scSpecTypeU32` ||
| ✅ | ✅ | `scSpecTypeI32` ||
| ✅ | ✅ | `scSpecTypeU64` ||
| ✅ | ✅ | `scSpecTypeI64` ||
| ✅ | ✅ | `scSpecTypeTimepoint` ||
| ✅ | ✅ | `scSpecTypeDuration` ||
| ✅ | ✅ | `scSpecTypeU128` ||
| ✅ | ✅ | `scSpecTypeI128` ||
| ✅ | ✅ | `scSpecTypeU256` ||
| ✅ | ✅ | `scSpecTypeI256` ||
| ✅ | ✅ | `scSpecTypeBytes` ||
| ✅ | ✅ | `scSpecTypeString` ||
| ✅ | ✅ | `scSpecTypeSymbol` ||
| ✅ | ✅ | `scSpecTypeAddress` ||
| ✅ | ✅ | `scSpecTypeOption` ||
| ✅ | ✅ | `scSpecTypeResult` ||
| ✅ | ✅ | `scSpecTypeVec` ||
| ✅ | ✅ | `scSpecTypeMap` ||
| ✅ | ✅ | `scSpecTypeTuple` ||
| ✅ | ✅ | `scSpecTypeBytesN` ||
| ✅ | ✅ | `scSpecTypeUdt` | `scSpecEntryUdtStructV0` |
| ✅ | ✅ | `scSpecTypeUdt` | `scSpecEntryUdtUnionV0` |
| ✅ | ✅ | `scSpecTypeUdt` | `scSpecEntryUdtEnumV0` |

## Network Environment

| Read | Write | Type | Comment |
| --- | --- | --- | --- |
| ✅ | ✅ | `scvBool` ||
| 🟥 | ✅ | `scvVoid` | Don't see a function ever having a void argument. |
| 🟥 | 🟥 | `scvError` | Working on it by parsing `Diagnostic Event` from the response. |
| ✅ | ✅ | `scvU32` ||
| ✅ | ✅ | `scvI32` ||
| ✅ | ✅ | `scvU64` ||
| ✅ | ✅ | `scvI64` ||
| ✅ | ✅ | `scvTimepoint` ||
| ✅ | ✅ | `scvDuration` ||
| ✅ | ✅ | `scvU128` ||
| ✅ | ✅ | `scvI128` ||
| ✅ | ✅ | `scvU256` ||
| ✅ | ✅ | `scvI256` ||
| ✅ | ✅ | `scvBytes` ||
| ✅ | ✅ | `scvString` ||
| ✅ | ✅ | `scvSymbol` ||
| ✅ | ✅ | `scvVec` ||
| ✅ | ✅ | `scvMap` ||
| ✅ | ✅ | `scvAddress` ||

Verify using this [Okashi](https://trunk.okashi.dev/playground/astrvtznqohfswtehpmwuxdxncaj) project.