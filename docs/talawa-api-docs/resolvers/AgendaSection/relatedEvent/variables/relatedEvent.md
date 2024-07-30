[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [resolvers/AgendaSection/relatedEvent](../README.md) / relatedEvent

# Variable: relatedEvent

\> `const` **relatedEvent**: [`AgendaSectionResolvers`](../../../../types/generatedGraphQLTypes/type-aliases/AgendaSectionResolvers.md)\[`"relatedEvent"`\]

Resolver function for the `relatedEvent` field of an `AgendaSection`.

This function retrieves the event related to a specific agenda section.

## Param

The parent object representing the agenda section. It contains information about the agenda section, including the ID of the related event.

## See

 - Event - The Event model used to interact with the events collection in the database.
 - AgendaSectionResolvers - The type definition for the resolvers of the AgendaSection fields.

## Defined in

[src/resolvers/AgendaSection/relatedEvent.ts:17](https://github.com/PalisadoesFoundation/talawa-api/blob/1f38da5423898626c6ebfa24896a9c3d008195c6/src/resolvers/AgendaSection/relatedEvent.ts#L17)