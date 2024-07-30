[**talawa-api**](../../../README.md) • **Docs**

***

[talawa-api](../../../modules.md) / [types/generatedGraphQLTypes](../README.md) / RecurrenceRuleInput

# Type Alias: RecurrenceRuleInput

\> **RecurrenceRuleInput**: `object`

## Type declaration

### count?

\> `optional` **count**: [`InputMaybe`](InputMaybe.md)\<[`Scalars`](Scalars.md)\[`"PositiveInt"`\]\[`"input"`\]\>

### frequency?

\> `optional` **frequency**: [`InputMaybe`](InputMaybe.md)\<[`Frequency`](Frequency.md)\>

### interval?

\> `optional` **interval**: [`InputMaybe`](InputMaybe.md)\<[`Scalars`](Scalars.md)\[`"PositiveInt"`\]\[`"input"`\]\>

### recurrenceEndDate?

\> `optional` **recurrenceEndDate**: [`InputMaybe`](InputMaybe.md)\<[`Scalars`](Scalars.md)\[`"Date"`\]\[`"input"`\]\>

### recurrenceStartDate?

\> `optional` **recurrenceStartDate**: [`InputMaybe`](InputMaybe.md)\<[`Scalars`](Scalars.md)\[`"Date"`\]\[`"input"`\]\>

### weekDayOccurenceInMonth?

\> `optional` **weekDayOccurenceInMonth**: [`InputMaybe`](InputMaybe.md)\<[`Scalars`](Scalars.md)\[`"Int"`\]\[`"input"`\]\>

### weekDays?

\> `optional` **weekDays**: [`InputMaybe`](InputMaybe.md)\<[`InputMaybe`](InputMaybe.md)\<[`WeekDays`](WeekDays.md)\>[]\>

## Defined in

[src/types/generatedGraphQLTypes.ts:2625](https://github.com/PalisadoesFoundation/talawa-api/blob/1f38da5423898626c6ebfa24896a9c3d008195c6/src/types/generatedGraphQLTypes.ts#L2625)