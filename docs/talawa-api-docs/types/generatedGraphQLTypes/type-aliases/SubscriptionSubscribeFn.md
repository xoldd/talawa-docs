[**talawa-api**](../../../README.md) • **Docs**

***

[talawa-api](../../../modules.md) / [types/generatedGraphQLTypes](../README.md) / SubscriptionSubscribeFn

# Type Alias: SubscriptionSubscribeFn()\<TResult, TParent, TContext, TArgs\>

\> **SubscriptionSubscribeFn**\<`TResult`, `TParent`, `TContext`, `TArgs`\>: (`parent`, `args`, `context`, `info`?) =\> `AsyncIterable`\<`TResult`\> \| `Promise`\<`AsyncIterable`\<`TResult`\>\>

## Type Parameters

• **TResult**

• **TParent**

• **TContext**

• **TArgs**

## Parameters

• **parent**: `TParent`

• **args**: `TArgs`

• **context**: `TContext`

• **info?**: `GraphQLResolveInfo`

## Returns

`AsyncIterable`\<`TResult`\> \| `Promise`\<`AsyncIterable`\<`TResult`\>\>

## Defined in

[src/types/generatedGraphQLTypes.ts:3183](https://github.com/PalisadoesFoundation/talawa-api/blob/1f38da5423898626c6ebfa24896a9c3d008195c6/src/types/generatedGraphQLTypes.ts#L3183)