[@iobroker/js-controller-adapter](../README.md) / [Exports](../modules.md) / [\<internal\>](../modules/internal_.md) / SupportedMessages

# Interface: SupportedMessages

[\<internal\>](../modules/internal_.md).SupportedMessages

Object which defines, if the adapter supports receiving messages via sendTo.
Additionally, it defines if specific messages are supported.
If one property is enabled, the object `system.adapter.<adaptername>.<adapterinstance>.messagebox will be created to send messages to the adapter (used for email, pushover, etc...)

## Table of contents

### Properties

- [custom](internal_.SupportedMessages.md#custom)
- [deviceManager](internal_.SupportedMessages.md#devicemanager)
- [getHistory](internal_.SupportedMessages.md#gethistory)
- [notifications](internal_.SupportedMessages.md#notifications)
- [stopInstance](internal_.SupportedMessages.md#stopinstance)

## Properties

### custom

• `Optional` **custom**: `boolean`

If custom messages are supported (same as legacy messagebox)

#### Defined in

[types-dev/objects.d.ts:495](https://github.com/ioBroker/ioBroker.js-controller/blob/bb39b56985d2141130fd7ada5e4d35b1a3779c05/packages/types-dev/objects.d.ts#L495)

___

### deviceManager

• `Optional` **deviceManager**: `boolean`

If adapter supports the device manager and thus responds to the corresponding messages

#### Defined in

[types-dev/objects.d.ts:501](https://github.com/ioBroker/ioBroker.js-controller/blob/bb39b56985d2141130fd7ada5e4d35b1a3779c05/packages/types-dev/objects.d.ts#L501)

___

### getHistory

• `Optional` **getHistory**: `boolean`

If adapter supports getHistory message.

#### Defined in

[types-dev/objects.d.ts:503](https://github.com/ioBroker/ioBroker.js-controller/blob/bb39b56985d2141130fd7ada5e4d35b1a3779c05/packages/types-dev/objects.d.ts#L503)

___

### notifications

• `Optional` **notifications**: `boolean`

If notification handling is supported, for information, see https://github.com/foxriver76/ioBroker.notification-manager#requirements-for-messaging-adapters

#### Defined in

[types-dev/objects.d.ts:497](https://github.com/ioBroker/ioBroker.js-controller/blob/bb39b56985d2141130fd7ada5e4d35b1a3779c05/packages/types-dev/objects.d.ts#L497)

___

### stopInstance

• `Optional` **stopInstance**: `number` \| `boolean`

If adapter supports signal stopInstance. Use number if you need more than 1000 ms for stop routine. The signal will be sent before stop to the adapter. (used if problems occurred with SIGTERM).

#### Defined in

[types-dev/objects.d.ts:499](https://github.com/ioBroker/ioBroker.js-controller/blob/bb39b56985d2141130fd7ada5e4d35b1a3779c05/packages/types-dev/objects.d.ts#L499)
