[**talawa-api**](../../../README.md) • **Docs**

***

[talawa-api](../../../modules.md) / [types/generatedGraphQLTypes](../README.md) / TypeResolveFn

# Type Alias: TypeResolveFn()\<TTypes, TParent, TContext\>

\> **TypeResolveFn**\<`TTypes`, `TParent`, `TContext`\>: (`parent`, `context`, `info`?) =\> [`Maybe`](Maybe.md)\<`TTypes`\> \| `Promise`\<[`Maybe`](Maybe.md)\<`TTypes`\>\>

## Type Parameters

• **TTypes**

• **TParent** = `object`

• **TContext** = `object`

## Parameters

• **parent**: `TParent`

• **context**: `TContext`

• **info?**: `GraphQLResolveInfo`

## Returns

[`Maybe`](Maybe.md)\<`TTypes`\> \| `Promise`\<[`Maybe`](Maybe.md)\<`TTypes`\>\>

## Defined in

[src/types/generatedGraphQLTypes.ts:3215](https://github.com/PalisadoesFoundation/talawa-api/blob/1f38da5423898626c6ebfa24896a9c3d008195c6/src/types/generatedGraphQLTypes.ts#L3215)