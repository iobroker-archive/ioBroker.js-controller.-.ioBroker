[**@iobroker/js-controller-adapter**](../../README.md) • **Docs**

***

[@iobroker/js-controller-adapter](../../globals.md) / [\<internal\>](../README.md) / Logger

# Interface: Logger

## Properties

### level

> **level**: [`LogLevel`](../type-aliases/LogLevel.md)

Verbosity of the log output

#### Defined in

[types-dev/index.d.ts:223](https://github.com/ioBroker/ioBroker.js-controller/blob/93db56665248b4cd78a78e2bab0647c80d6ccf9f/packages/types-dev/index.d.ts#L223)

## Methods

### debug()

> **debug**(`message`): `void`

log a message with debug level

#### Parameters

• **message**: `string`

#### Returns

`void`

#### Defined in

[types-dev/index.d.ts:214](https://github.com/ioBroker/ioBroker.js-controller/blob/93db56665248b4cd78a78e2bab0647c80d6ccf9f/packages/types-dev/index.d.ts#L214)

***

### error()

> **error**(`message`): `void`

log a message with error severity

#### Parameters

• **message**: `string`

#### Returns

`void`

#### Defined in

[types-dev/index.d.ts:220](https://github.com/ioBroker/ioBroker.js-controller/blob/93db56665248b4cd78a78e2bab0647c80d6ccf9f/packages/types-dev/index.d.ts#L220)

***

### info()

> **info**(`message`): `void`

log a message with info level (default output level for all adapters)

#### Parameters

• **message**: `string`

#### Returns

`void`

#### Defined in

[types-dev/index.d.ts:216](https://github.com/ioBroker/ioBroker.js-controller/blob/93db56665248b4cd78a78e2bab0647c80d6ccf9f/packages/types-dev/index.d.ts#L216)

***

### silly()

> **silly**(`message`): `void`

log a message with silly level

#### Parameters

• **message**: `string`

#### Returns

`void`

#### Defined in

[types-dev/index.d.ts:212](https://github.com/ioBroker/ioBroker.js-controller/blob/93db56665248b4cd78a78e2bab0647c80d6ccf9f/packages/types-dev/index.d.ts#L212)

***

### warn()

> **warn**(`message`): `void`

log a message with warning severity

#### Parameters

• **message**: `string`

#### Returns

`void`

#### Defined in

[types-dev/index.d.ts:218](https://github.com/ioBroker/ioBroker.js-controller/blob/93db56665248b4cd78a78e2bab0647c80d6ccf9f/packages/types-dev/index.d.ts#L218)
