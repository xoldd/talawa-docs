[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [resolvers/Subscription/messageSentToGroupChat](../README.md) / filterFunction

# Function: filterFunction()

> **filterFunction**(`payload`, `variables`): `Promise`\<`boolean`\>

This function is used to filter the subscription payload based on the current user's membership in the group chat.

## Parameters

• **payload**: `any`

The payload of the subscription message.

• **variables**: `any`

## Returns

`Promise`\<`boolean`\>

A promise that resolves to a boolean value indicating whether the current user is a member of the group chat.

## Defined in

[src/resolvers/Subscription/messageSentToGroupChat.ts:15](https://github.com/PalisadoesFoundation/talawa-api/blob/6712e9940a5702665afc506fa9f6e9d7e1dc7991/src/resolvers/Subscription/messageSentToGroupChat.ts#L15)
