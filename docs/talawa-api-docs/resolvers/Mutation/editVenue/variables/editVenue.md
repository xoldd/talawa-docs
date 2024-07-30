[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [resolvers/Mutation/editVenue](../README.md) / editVenue

# Variable: editVenue

\> `const` **editVenue**: [`MutationResolvers`](../../../../types/generatedGraphQLTypes/type-aliases/MutationResolvers.md)\[`"editVenue"`\]

This function enables to edit a venue.

## Param

parent of current request

## Param

payload provided with the request

## Param

context of entire application

## Remarks

The following checks are done:
1. If the user exists
2. If the organization exists
3. If the venue exists
4. If the user is authorized
5. If the venue details are valid
5. If the venue already exists

## Defined in

[src/resolvers/Mutation/editVenue.ts:35](https://github.com/PalisadoesFoundation/talawa-api/blob/1f38da5423898626c6ebfa24896a9c3d008195c6/src/resolvers/Mutation/editVenue.ts#L35)