[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [utilities/graphQLConnection/generateDefaultGraphQLConnection](../README.md) / DefaultGraphQLConnectionEdge

# Type Alias: DefaultGraphQLConnectionEdge\<T0\>

\> **DefaultGraphQLConnectionEdge**\<`T0`\>: `object`

This is typescript type of a base graphQL connection edge object. This connection edge object
can be extended to create a custom connection edge object as long as the new connection edge
object adheres to the default type of this base connection edge object.

## Type Parameters

• **T0**

## Type declaration

### cursor

\> **cursor**: `string`

### node

\> **node**: `T0`

## Defined in

[src/utilities/graphQLConnection/generateDefaultGraphQLConnection.ts:8](https://github.com/PalisadoesFoundation/talawa-api/blob/1f38da5423898626c6ebfa24896a9c3d008195c6/src/utilities/graphQLConnection/generateDefaultGraphQLConnection.ts#L8)