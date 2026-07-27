[**Tikka SDK v0.1.0**](../../README.md)

***

[Tikka SDK](../../modules.md) / [index](../README.md) / GetParticipationParams

# Interface: GetParticipationParams

Defined in: [modules/user/user.types.ts:36](https://github.com/AvatarMiiDe/tikka/blob/7d24432df51b3bab3c505c8fb4f89ccb1415fee8/sdk/src/modules/user/user.types.ts#L36)

Parameters for querying user participation statistics.

## Example

```ts
const params: GetParticipationParams = {
  address: userAddress
};
const result = await userService.getParticipation(params);
```

## Properties

### address

> **address**: `string`

Defined in: [modules/user/user.types.ts:38](https://github.com/AvatarMiiDe/tikka/blob/7d24432df51b3bab3c505c8fb4f89ccb1415fee8/sdk/src/modules/user/user.types.ts#L38)

User's Stellar public key address to query
