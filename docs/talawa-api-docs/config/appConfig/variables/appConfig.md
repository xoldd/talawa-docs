[**talawa-api**](../../../README.md) • **Docs**

***

[talawa-api](../../../modules.md) / [config/appConfig](../README.md) / appConfig

# Variable: appConfig

> `const` **appConfig**: `object`

Application configuration settings.
This object contains various configuration options for the application.

## Type declaration

### colorize\_logs

> **colorize\_logs**: `undefined` \| `string` = `process.env.COLORIZE_LOGS`

Determines if logs should be colorized.

### defaultLocale

> **defaultLocale**: `string` = `"en"`

The default language for the application.

### env

> **env**: `undefined` \| `string` = `process.env.NODE_ENV`

The current environment of the application (e.g., 'development', 'production').

### log\_level

> **log\_level**: `undefined` \| `string` = `process.env.LOG_LEVEL`

The logging level for the application (e.g., 'info', 'error').

### supportedLocales

> **supportedLocales**: `string`[]

An array of supported language for the application.

## Defined in

[src/config/appConfig.ts:5](https://github.com/PalisadoesFoundation/talawa-api/blob/6712e9940a5702665afc506fa9f6e9d7e1dc7991/src/config/appConfig.ts#L5)
