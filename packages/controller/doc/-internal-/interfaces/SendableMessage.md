[**@iobroker/js-controller-adapter**](../../README.md) • **Docs**

***

[@iobroker/js-controller-adapter](../../globals.md) / [\<internal\>](../README.md) / SendableMessage

# Interface: SendableMessage

## Extended by

- [`Message`](Message.md)

## Properties

### callback?

> `optional` **callback**: [`MessageCallbackInfo`](MessageCallbackInfo.md)

Callback information. This is set when the source expects a response

#### Defined in

[types-dev/index.d.ts:271](https://github.com/ioBroker/ioBroker.js-controller/blob/99469b9944509b9c64b9a28da6d8dabf17a8ea74/packages/types-dev/index.d.ts#L271)

***

### command

> **command**: `string`

The command to be executed

#### Defined in

[types-dev/index.d.ts:265](https://github.com/ioBroker/ioBroker.js-controller/blob/99469b9944509b9c64b9a28da6d8dabf17a8ea74/packages/types-dev/index.d.ts#L265)

***

### from

> **from**: `string`

The source of this message

#### Defined in

[types-dev/index.d.ts:269](https://github.com/ioBroker/ioBroker.js-controller/blob/99469b9944509b9c64b9a28da6d8dabf17a8ea74/packages/types-dev/index.d.ts#L269)

***

### message

> **message**: `any`

The message payload

#### Defined in

[types-dev/index.d.ts:267](https://github.com/ioBroker/ioBroker.js-controller/blob/99469b9944509b9c64b9a28da6d8dabf17a8ea74/packages/types-dev/index.d.ts#L267)
