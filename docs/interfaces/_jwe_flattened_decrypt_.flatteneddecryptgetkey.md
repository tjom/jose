# Interface: FlattenedDecryptGetKey

Interface for Flattened JWE Decryption dynamic key resolution.
No token components have been verified at the time of this function call.

## Callable

▸ (`protectedHeader`: [JWEHeaderParameters](_types_d_.jweheaderparameters.md) \| undefined, `token`: [FlattenedJWE](_types_d_.flattenedjwe.md)): Promise\<[KeyLike](../types/_types_d_.keylike.md)>

*Defined in [src/types.d.ts:77](https://github.com/panva/jose/blob/v3.3.2/src/types.d.ts#L77)*

Interface for Flattened JWE Decryption dynamic key resolution.
No token components have been verified at the time of this function call.

#### Parameters:

Name | Type |
------ | ------ |
`protectedHeader` | [JWEHeaderParameters](_types_d_.jweheaderparameters.md) \| undefined |
`token` | [FlattenedJWE](_types_d_.flattenedjwe.md) |

**Returns:** Promise\<[KeyLike](../types/_types_d_.keylike.md)>
