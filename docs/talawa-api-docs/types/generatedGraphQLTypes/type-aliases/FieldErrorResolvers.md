[**talawa-api**](../../../README.md) • **Docs**

***

[talawa-api](../../../modules.md) / [types/generatedGraphQLTypes](../README.md) / FieldErrorResolvers

# Type Alias: FieldErrorResolvers\<ContextType, ParentType\>

\> **FieldErrorResolvers**\<`ContextType`, `ParentType`\>: `object`

## Type Parameters

• **ContextType** = `any`

• **ParentType** *extends* [`ResolversParentTypes`](ResolversParentTypes.md)\[`"FieldError"`\] = [`ResolversParentTypes`](ResolversParentTypes.md)\[`"FieldError"`\]

## Type declaration

### \_\_resolveType

\> **\_\_resolveType**: [`TypeResolveFn`](TypeResolveFn.md)\<`"InvalidCursor"` \| `"MaximumLengthError"` \| `"MaximumValueError"` \| `"MinimumLengthError"` \| `"MinimumValueError"`, `ParentType`, `ContextType`\>

### message?

\> `optional` **message**: [`Resolver`](Resolver.md)\<[`ResolversTypes`](ResolversTypes.md)\[`"String"`\], `ParentType`, `ContextType`\>

### path?

\> `optional` **path**: [`Resolver`](Resolver.md)\<[`ResolversTypes`](ResolversTypes.md)\[`"String"`\][], `ParentType`, `ContextType`\>

## Defined in

[src/types/generatedGraphQLTypes.ts:4073](https://github.com/PalisadoesFoundation/talawa-api/blob/1f38da5423898626c6ebfa24896a9c3d008195c6/src/types/generatedGraphQLTypes.ts#L4073)