[**talawa-api**](../../../README.md) • **Docs**

***

[talawa-api](../../../modules.md) / [types/generatedGraphQLTypes](../README.md) / CreateDirectChatPayloadResolvers

# Type Alias: CreateDirectChatPayloadResolvers\<ContextType, ParentType\>

\> **CreateDirectChatPayloadResolvers**\<`ContextType`, `ParentType`\>: `object`

## Type Parameters

• **ContextType** = `any`

• **ParentType** *extends* [`ResolversParentTypes`](ResolversParentTypes.md)\[`"createDirectChatPayload"`\] = [`ResolversParentTypes`](ResolversParentTypes.md)\[`"createDirectChatPayload"`\]

## Type declaration

### \_\_isTypeOf?

\> `optional` **\_\_isTypeOf**: [`IsTypeOfResolverFn`](IsTypeOfResolverFn.md)\<`ParentType`, `ContextType`\>

### directChat?

\> `optional` **directChat**: [`Resolver`](Resolver.md)\<[`Maybe`](Maybe.md)\<[`ResolversTypes`](ResolversTypes.md)\[`"DirectChat"`\]\>, `ParentType`, `ContextType`\>

### userErrors?

\> `optional` **userErrors**: [`Resolver`](Resolver.md)\<[`ResolversTypes`](ResolversTypes.md)\[`"CreateDirectChatError"`\][], `ParentType`, `ContextType`\>

## Defined in

[src/types/generatedGraphQLTypes.ts:4775](https://github.com/PalisadoesFoundation/talawa-api/blob/1f38da5423898626c6ebfa24896a9c3d008195c6/src/types/generatedGraphQLTypes.ts#L4775)