[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [resolvers/Event/attendees](../README.md) / attendees

# Variable: attendees

\> `const` **attendees**: [`EventResolvers`](../../../../types/generatedGraphQLTypes/type-aliases/EventResolvers.md)\[`"attendees"`\]

Resolver function for the `attendees` field of an `Event`.

This function retrieves the attendees of an event.

## Param

The parent object representing the event. It contains information about the event, including the ID of the event.

## See

 - EventAttendee - The EventAttendee model used to interact with the event attendees collection in the database.
 - EventResolvers - The type definition for the resolvers of the Event fields.

## Defined in

[src/resolvers/Event/attendees.ts:16](https://github.com/PalisadoesFoundation/talawa-api/blob/1f38da5423898626c6ebfa24896a9c3d008195c6/src/resolvers/Event/attendees.ts#L16)