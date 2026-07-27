[**Tikka SDK v0.1.0**](../../README.md)

***

[Tikka SDK](../../modules.md) / [index](../README.md) / verifyResponse

# Function: verifyResponse()

> **verifyResponse**(`options`): `Promise`\<`string`\>

Defined in: [auth/sep10.ts:203](https://github.com/AvatarMiiDe/tikka/blob/7d24432df51b3bab3c505c8fb4f89ccb1415fee8/sdk/src/auth/sep10.ts#L203)

Verify a signed SEP-10 response transaction and return the client public key on success.

## Parameters

### options

[`VerifyResponseOptions`](../interfaces/VerifyResponseOptions.md)

VerifyResponseOptions

## Returns

`Promise`\<`string`\>

verified client account

## Example

```ts
const verifiedClient = await verifyResponse({
  signedChallenge: responseXdr,
  serverAccount: serverPublicKey,
  clientAccount: clientPublicKey,
  anchorDomain: 'example.com',
  networkPassphrase: Networks.TESTNET,
  nonceValidator: async (nonce) => { return !nonceExists(nonce); },
});
```
