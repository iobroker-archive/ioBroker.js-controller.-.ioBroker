[@iobroker/js-controller-adapter](../README.md) / [Exports](../modules.md) / [\<internal\>](../modules/internal_.md) / ChannelObject

# Interface: ChannelObject

[\<internal\>](../modules/internal_.md).ChannelObject

## Hierarchy

- [`BaseObject`](internal_.BaseObject.md)

  ↳ **`ChannelObject`**

## Table of contents

### Properties

- [\_id](internal_.ChannelObject.md#_id)
- [acl](internal_.ChannelObject.md#acl)
- [common](internal_.ChannelObject.md#common)
- [enums](internal_.ChannelObject.md#enums)
- [from](internal_.ChannelObject.md#from)
- [native](internal_.ChannelObject.md#native)
- [nonEdit](internal_.ChannelObject.md#nonedit)
- [ts](internal_.ChannelObject.md#ts)
- [type](internal_.ChannelObject.md#type)
- [user](internal_.ChannelObject.md#user)

## Properties

### \_id

• **\_id**: `string`

The ID of this object

#### Inherited from

[BaseObject](internal_.BaseObject.md).[_id](internal_.BaseObject.md#_id)

#### Defined in

[types-dev/objects.d.ts:901](https://github.com/ioBroker/ioBroker.js-controller/blob/610f8794837c90e96c314dec3a8f4af930e84d94/packages/types-dev/objects.d.ts#L901)

___

### acl

• `Optional` **acl**: [`ObjectACL`](internal_.ObjectACL.md)

#### Inherited from

[BaseObject](internal_.BaseObject.md).[acl](internal_.BaseObject.md#acl)

#### Defined in

[types-dev/objects.d.ts:908](https://github.com/ioBroker/ioBroker.js-controller/blob/610f8794837c90e96c314dec3a8f4af930e84d94/packages/types-dev/objects.d.ts#L908)

___

### common

• **common**: [`ChannelCommon`](internal_.ChannelCommon.md)

#### Overrides

[BaseObject](internal_.BaseObject.md).[common](internal_.BaseObject.md#common)

#### Defined in

[types-dev/objects.d.ts:930](https://github.com/ioBroker/ioBroker.js-controller/blob/610f8794837c90e96c314dec3a8f4af930e84d94/packages/types-dev/objects.d.ts#L930)

___

### enums

• `Optional` **enums**: `Record`\<`string`, `string` \| [`Translated`](../modules/internal_.md#translated)\>

#### Inherited from

[BaseObject](internal_.BaseObject.md).[enums](internal_.BaseObject.md#enums)

#### Defined in

[types-dev/objects.d.ts:907](https://github.com/ioBroker/ioBroker.js-controller/blob/610f8794837c90e96c314dec3a8f4af930e84d94/packages/types-dev/objects.d.ts#L907)

___

### from

• `Optional` **from**: `string`

#### Inherited from

[BaseObject](internal_.BaseObject.md).[from](internal_.BaseObject.md#from)

#### Defined in

[types-dev/objects.d.ts:909](https://github.com/ioBroker/ioBroker.js-controller/blob/610f8794837c90e96c314dec3a8f4af930e84d94/packages/types-dev/objects.d.ts#L909)

___

### native

• **native**: `Record`\<`string`, `any`\>

#### Inherited from

[BaseObject](internal_.BaseObject.md).[native](internal_.BaseObject.md#native)

#### Defined in

[types-dev/objects.d.ts:905](https://github.com/ioBroker/ioBroker.js-controller/blob/610f8794837c90e96c314dec3a8f4af930e84d94/packages/types-dev/objects.d.ts#L905)

___

### nonEdit

• `Optional` **nonEdit**: [`NonEditable`](internal_.NonEditable.md)

These properties can only be edited if the correct password is provided

#### Inherited from

[BaseObject](internal_.BaseObject.md).[nonEdit](internal_.BaseObject.md#nonedit)

#### Defined in

[types-dev/objects.d.ts:914](https://github.com/ioBroker/ioBroker.js-controller/blob/610f8794837c90e96c314dec3a8f4af930e84d94/packages/types-dev/objects.d.ts#L914)

___

### ts

• `Optional` **ts**: `number`

#### Inherited from

[BaseObject](internal_.BaseObject.md).[ts](internal_.BaseObject.md#ts)

#### Defined in

[types-dev/objects.d.ts:912](https://github.com/ioBroker/ioBroker.js-controller/blob/610f8794837c90e96c314dec3a8f4af930e84d94/packages/types-dev/objects.d.ts#L912)

___

### type

• **type**: ``"channel"``

#### Overrides

[BaseObject](internal_.BaseObject.md).[type](internal_.BaseObject.md#type)

#### Defined in

[types-dev/objects.d.ts:929](https://github.com/ioBroker/ioBroker.js-controller/blob/610f8794837c90e96c314dec3a8f4af930e84d94/packages/types-dev/objects.d.ts#L929)

___

### user

• `Optional` **user**: `string`

The user who created or updated this object

#### Inherited from

[BaseObject](internal_.BaseObject.md).[user](internal_.BaseObject.md#user)

#### Defined in

[types-dev/objects.d.ts:911](https://github.com/ioBroker/ioBroker.js-controller/blob/610f8794837c90e96c314dec3a8f4af930e84d94/packages/types-dev/objects.d.ts#L911)
