[**Tikka SDK v0.1.0**](../../README.md)

***

[Tikka SDK](../../modules.md) / [index](../README.md) / AdminWriteOptions

# Interface: AdminWriteOptions

Defined in: [modules/admin/admin.types.ts:94](https://github.com/AvatarMiiDe/tikka/blob/7d24432df51b3bab3c505c8fb4f89ccb1415fee8/sdk/src/modules/admin/admin.types.ts#L94)

Optional parameters for admin write operations.

## Example

```ts
const options: AdminWriteOptions = {
  memo: 'pause_during_maintenance'
};
const result = await adminService.pause(options);
```

## Properties

### memo?

> `optional` **memo?**: [`TxMemo`](../type-aliases/TxMemo.md)

Defined in: [modules/admin/admin.types.ts:100](https://github.com/AvatarMiiDe/tikka/blob/7d24432df51b3bab3c505c8fb4f89ccb1415fee8/sdk/src/modules/admin/admin.types.ts#L100)

Optional transaction memo for tracking or external integrations.
Supports text (≤28 bytes), numeric id, or 32-byte hash.
Useful for on-chain record-keeping and audit trails.
