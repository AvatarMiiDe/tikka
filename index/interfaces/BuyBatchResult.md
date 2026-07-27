[**Tikka SDK v0.1.0**](../../README.md)

***

[Tikka SDK](../../modules.md) / [index](../README.md) / BuyBatchResult

# Interface: BuyBatchResult

Defined in: [modules/ticket/ticket.types.ts:165](https://github.com/AvatarMiiDe/tikka/blob/7d24432df51b3bab3c505c8fb4f89ccb1415fee8/sdk/src/modules/ticket/ticket.types.ts#L165)

Result of batch ticket purchases.
Provides individual results for each raffle and aggregate transaction info.

## Properties

### feePaid

> **feePaid**: `string`

Defined in: [modules/ticket/ticket.types.ts:173](https://github.com/AvatarMiiDe/tikka/blob/7d24432df51b3bab3c505c8fb4f89ccb1415fee8/sdk/src/modules/ticket/ticket.types.ts#L173)

Total transaction fee paid in stroops

***

### ledger

> **ledger**: `number`

Defined in: [modules/ticket/ticket.types.ts:171](https://github.com/AvatarMiiDe/tikka/blob/7d24432df51b3bab3c505c8fb4f89ccb1415fee8/sdk/src/modules/ticket/ticket.types.ts#L171)

Ledger number where last transaction was confirmed

***

### results

> **results**: [`BatchPurchaseResult`](BatchPurchaseResult.md)[]

Defined in: [modules/ticket/ticket.types.ts:167](https://github.com/AvatarMiiDe/tikka/blob/7d24432df51b3bab3c505c8fb4f89ccb1415fee8/sdk/src/modules/ticket/ticket.types.ts#L167)

Individual results for each raffle purchase

***

### transactionHash

> **transactionHash**: `string`

Defined in: [modules/ticket/ticket.types.ts:169](https://github.com/AvatarMiiDe/tikka/blob/7d24432df51b3bab3c505c8fb4f89ccb1415fee8/sdk/src/modules/ticket/ticket.types.ts#L169)

Transaction hash for confirmation (hash of last successful transaction)
