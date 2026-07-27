[**Tikka SDK v0.1.0**](../../README.md)

***

[Tikka SDK](../../modules.md) / [index](../README.md) / toTypedSdkError

# Function: toTypedSdkError()

> **toTypedSdkError**(`err`): [`TikkaSdkError`](../classes/TikkaSdkError.md)

Defined in: [utils/errors.ts:295](https://github.com/AvatarMiiDe/tikka/blob/7d24432df51b3bab3c505c8fb4f89ccb1415fee8/sdk/src/utils/errors.ts#L295)

Upgrades a generic caught error into the most specific `TikkaSdkError`
subtype possible. If `err` is already a `TikkaSdkError` with code
`ContractError` and a string `cause` containing a recognizable Soroban
error code, it is converted into the matching typed error. Otherwise the
error is returned unchanged (if already a `TikkaSdkError`) or wrapped.

## Parameters

### err

`unknown`

## Returns

[`TikkaSdkError`](../classes/TikkaSdkError.md)
