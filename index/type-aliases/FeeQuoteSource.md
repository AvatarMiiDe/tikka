[**Tikka SDK v0.1.0**](../../README.md)

***

[Tikka SDK](../../modules.md) / [index](../README.md) / FeeQuoteSource

# Type Alias: FeeQuoteSource

> **FeeQuoteSource** = `"simulation"` \| `"fallback"`

Defined in: [fee-estimator/fee-estimator.types.ts:10](https://github.com/AvatarMiiDe/tikka/blob/7d24432df51b3bab3c505c8fb4f89ccb1415fee8/sdk/src/fee-estimator/fee-estimator.types.ts#L10)

How the fee estimate was derived.
- `simulation` — live `simulateTransaction` RPC call (most accurate)
- `fallback`   — static heuristic used when simulation is unavailable
