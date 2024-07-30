[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [resolvers/CheckIn/user](../README.md) / user

# Variable: user

\> `const` **user**: [`CheckInResolvers`](../../../../types/generatedGraphQLTypes/type-aliases/CheckInResolvers.md)\[`"user"`\]

Resolver function for the `user` field of a `CheckIn`.

This function retrieves the user who checked in to an event.

## Param

The parent object representing the check-in. It contains information about the check-in, including the ID of the event attendee who checked in.

## See

 - EventAttendee - The EventAttendee model used to interact with the event attendees collection in the database.
 - CheckInResolvers - The type definition for the resolvers of the CheckIn fields.

## Defined in

[src/resolvers/CheckIn/user.ts:16](https://github.com/PalisadoesFoundation/talawa-api/blob/1f38da5423898626c6ebfa24896a9c3d008195c6/src/resolvers/CheckIn/user.ts#L16)