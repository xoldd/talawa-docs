[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [resolvers/Query/agendaCategory](../README.md) / agendaCategory

# Variable: agendaCategory

> `const` **agendaCategory**: [`QueryResolvers`](../../../../types/generatedGraphQLTypes/type-aliases/QueryResolvers.md)\[`"agendaCategory"`\]

This is a resolver function for the GraphQL query 'agendaCategory'.

This resolver fetches an agenda category by its ID.

## Param

The parent object, not used in this resolver.

## Param

The input arguments for the query.

## Throws

`NotFoundError` If the agenda category is not found.

## Throws

`InternalServerError` For other potential issues during agenda category fetching.

## Defined in

[src/resolvers/Query/agendaCategory.ts:19](https://github.com/PalisadoesFoundation/talawa-api/blob/6712e9940a5702665afc506fa9f6e9d7e1dc7991/src/resolvers/Query/agendaCategory.ts#L19)
