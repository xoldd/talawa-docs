[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [resolvers/Organization/members](../README.md) / members

# Variable: members

\> `const` **members**: [`OrganizationResolvers`](../../../../types/generatedGraphQLTypes/type-aliases/OrganizationResolvers.md)\[`"members"`\]

Resolver function for the `members` field of an `Organization`.

This function retrieves the users who are members of a specific organization.

## Param

The parent object representing the organization. It contains information about the organization, including the IDs of the users who are members of it.

## See

 - User - The User model used to interact with the users collection in the database.
 - OrganizationResolvers - The type definition for the resolvers of the Organization fields.

## Defined in

[src/resolvers/Organization/members.ts:16](https://github.com/PalisadoesFoundation/talawa-api/blob/1f38da5423898626c6ebfa24896a9c3d008195c6/src/resolvers/Organization/members.ts#L16)