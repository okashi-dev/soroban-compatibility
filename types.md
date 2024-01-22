# Support for Soroban Types

## Input

| Read | Write | Type | Comment |
| --- | --- | --- | --- |
| 🟨 | ✅ | `scSpecTypeVal` | Working on it. |
| ✅ | ✅ | `scSpecTypeBool` ||
| 🟥 | ✅ | `scSpecTypeVoid` | Don't see a function ever having a void argument. |
| 🟥 | ✅ | `scSpecTypeError` | Don't see how this could ever be an argument. |
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

Verify using this [Okashi](https://trunk.okashi.dev/playground/astrvtznqohfswtehpmwuxdxncaj) project.