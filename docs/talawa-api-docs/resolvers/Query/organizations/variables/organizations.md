[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [resolvers/Query/organizations](../README.md) / organizations

# Variable: organizations

\> `const` **organizations**: [`QueryResolvers`](../../../../types/generatedGraphQLTypes/type-aliases/QueryResolvers.md)\[`"organizations"`\]

If a 'id' is specified, this query will return an organisation;
otherwise, it will return all organisations with a size of limit 100.

## Param

## Param

An object containing `orderBy` and `id` of the Organization.

## Remarks

`id` in the args is optional.

## Defined in

[src/resolvers/Query/organizations.ts:16](https://github.com/PalisadoesFoundation/talawa-api/blob/1f38da5423898626c6ebfa24896a9c3d008195c6/src/resolvers/Query/organizations.ts#L16)