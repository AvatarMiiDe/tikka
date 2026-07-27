[**Tikka SDK v0.1.0**](../../README.md)

***

[Tikka SDK](../../modules.md) / [index](../README.md) / BuyTicketsParams

# Interface: BuyTicketsParams

Defined in: [modules/ticket/ticket.types.ts:31](https://github.com/AvatarMiiDe/tikka/blob/7d24432df51b3bab3c505c8fb4f89ccb1415fee8/sdk/src/modules/ticket/ticket.types.ts#L31)

Parameters for purchasing multiple tickets in a batch.

## Properties

### count

> **count**: `number`

Defined in: [modules/ticket/ticket.types.ts:35](https://github.com/AvatarMiiDe/tikka/blob/7d24432df51b3bab3c505c8fb4f89ccb1415fee8/sdk/src/modules/ticket/ticket.types.ts#L35)

Number of tickets to purchase (1-1000)

***

### maxPricePerTicket

> **maxPricePerTicket**: `string`

Defined in: [modules/ticket/ticket.types.ts:37](https://github.com/AvatarMiiDe/tikka/blob/7d24432df51b3bab3c505c8fb4f89ccb1415fee8/sdk/src/modules/ticket/ticket.types.ts#L37)

Maximum acceptable price per ticket in stroops

***

### memo?

> `optional` **memo?**: [`TxMemo`](../type-aliases/TxMemo.md)

Defined in: [modules/ticket/ticket.types.ts:41](https://github.com/AvatarMiiDe/tikka/blob/7d24432df51b3bab3c505c8fb4f89ccb1415fee8/sdk/src/modules/ticket/ticket.types.ts#L41)

Optional transaction memo for tracking or external integrations.

***

### raffleId

> **raffleId**: `number`

Defined in: [modules/ticket/ticket.types.ts:33](https://github.com/AvatarMiiDe/tikka/blob/7d24432df51b3bab3c505c8fb4f89ccb1415fee8/sdk/src/modules/ticket/ticket.types.ts#L33)

Raffle ID (must be positive integer)
