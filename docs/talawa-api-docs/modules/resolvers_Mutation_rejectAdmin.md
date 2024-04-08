[talawa-api](../README.md) / [Exports](../modules.md) / resolvers/Mutation/rejectAdmin

# Module: resolvers/Mutation/rejectAdmin

## Table of contents

### Variables

- [rejectAdmin](resolvers_Mutation_rejectAdmin.md#rejectadmin)

## Variables

### rejectAdmin

• `Const` **rejectAdmin**: [`MutationResolvers`](types_generatedGraphQLTypes.md#mutationresolvers)[``"rejectAdmin"``]

This function enables to reject an admin.

**`Param`**

parent of current request

**`Param`**

payload provided with the request

**`Param`**

context of entire application

**`Remarks`**

The following checks are done:
1. If the user exists
2.If the user has appProfile or not (if not, then the user is not a superadmin).
3. If the user is the SUPERADMIN of the organization.
4. If the user to be removed exists.

#### Defined in

[src/resolvers/Mutation/rejectAdmin.ts:22](https://github.com/PalisadoesFoundation/talawa-api/blob/e5f7a9d/src/resolvers/Mutation/rejectAdmin.ts#L22)