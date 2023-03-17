<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## PHP class

<b>Signature:</b>

```typescript
class PHP implements WithPHPIniBindings, WithFilesystem, WithNodeFilesystem, WithCLI, WithRun
```

<b>Implements:</b> [WithPHPIniBindings](./client.withphpinibindings.md)<!-- -->, [WithFilesystem](./client.withfilesystem.md)<!-- -->, [WithNodeFilesystem](./client.withnodefilesystem.md)<!-- -->, [WithCLI](./client.withcli.md)<!-- -->, [WithRun](./client.withrun.md)

## Remarks

The constructor for this class is marked as internal. Third-party code should not call the constructor directly or create subclasses that extend the `PHP` class.

## Methods

### addServerGlobalEntry<!-- -->(<!-- -->key<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->, value<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->)<!-- -->: [void](https://www.typescriptlang.org/docs/handbook/2/functions.html#void)

### cli<!-- -->(<!-- -->argv<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->[]<!-- -->)<!-- -->: [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)<!-- -->&lt;[number](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->&gt;

### fileExists<!-- -->(<!-- -->path<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->)<!-- -->: [boolean](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)

### initializeRuntime<!-- -->(<!-- -->runtimeId<!-- -->: [PHPRuntimeId](./client.phpruntimeid.md)<!-- -->)<!-- -->: [void](https://www.typescriptlang.org/docs/handbook/2/functions.html#void)

### isDir<!-- -->(<!-- -->path<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->)<!-- -->: [boolean](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)

### listFiles<!-- -->(<!-- -->path<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->)<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->[]

### mkdirTree<!-- -->(<!-- -->path<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->)<!-- -->: [void](https://www.typescriptlang.org/docs/handbook/2/functions.html#void)

### mount<!-- -->(<!-- -->settings<!-- -->: [MountSettings](./client.mountsettings.md)<!-- -->, path<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->)<!-- -->: [void](https://www.typescriptlang.org/docs/handbook/2/functions.html#void)

### readFileAsBuffer<!-- -->(<!-- -->path<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->)<!-- -->: [Uint8Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Uint8Array)

### readFileAsText<!-- -->(<!-- -->path<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->)<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)

### run<!-- -->(<!-- -->request?<!-- -->: [PHPRequest](./client.phprequest.md)<!-- -->)<!-- -->: [PHPResponse](./client.phpresponse.md)

-   `request` – Optional.

### setPhpIniEntry<!-- -->(<!-- -->key<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->, value<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->)<!-- -->: [void](https://www.typescriptlang.org/docs/handbook/2/functions.html#void)

### setPhpIniPath<!-- -->(<!-- -->path<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->)<!-- -->: [void](https://www.typescriptlang.org/docs/handbook/2/functions.html#void)

### setSkipShebang<!-- -->(<!-- -->shouldSkip<!-- -->: [boolean](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->)<!-- -->: [void](https://www.typescriptlang.org/docs/handbook/2/functions.html#void)

### unlink<!-- -->(<!-- -->path<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->)<!-- -->: [void](https://www.typescriptlang.org/docs/handbook/2/functions.html#void)

### writeFile<!-- -->(<!-- -->path<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->, data<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->|[Uint8Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Uint8Array)<!-- -->)<!-- -->: [void](https://www.typescriptlang.org/docs/handbook/2/functions.html#void)