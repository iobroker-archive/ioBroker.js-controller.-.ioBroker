[@iobroker/js-controller-adapter](../README.md) / [Exports](../modules.md) / [\<internal\>](../modules/internal_.md) / PartialDeviceObject

# Interface: PartialDeviceObject

[\<internal\>](../modules/internal_.md).PartialDeviceObject

## Hierarchy

- `Partial`\<`Omit`\<[`DeviceObject`](internal_.DeviceObject.md), ``"common"``\>\>

  ↳ **`PartialDeviceObject`**

## Table of contents

### Properties

- [\_id](internal_.PartialDeviceObject.md#_id)
- [acl](internal_.PartialDeviceObject.md#acl)
- [common](internal_.PartialDeviceObject.md#common)
- [enums](internal_.PartialDeviceObject.md#enums)
- [from](internal_.PartialDeviceObject.md#from)
- [native](internal_.PartialDeviceObject.md#native)
- [nonEdit](internal_.PartialDeviceObject.md#nonedit)
- [ts](internal_.PartialDeviceObject.md#ts)
- [type](internal_.PartialDeviceObject.md#type)
- [user](internal_.PartialDeviceObject.md#user)

## Properties

### \_id

• `Optional` **\_id**: `string`

The ID of this object

#### Inherited from

Partial.\_id

#### Defined in

[types-dev/objects.d.ts:901](https://github.com/ioBroker/ioBroker.js-controller/blob/610f8794837c90e96c314dec3a8f4af930e84d94/packages/types-dev/objects.d.ts#L901)

___

### acl

• `Optional` **acl**: [`ObjectACL`](internal_.ObjectACL.md)

#### Inherited from

Partial.acl

#### Defined in

[types-dev/objects.d.ts:908](https://github.com/ioBroker/ioBroker.js-controller/blob/610f8794837c90e96c314dec3a8f4af930e84d94/packages/types-dev/objects.d.ts#L908)

___

### common

• `Optional` **common**: `Partial`\<[`DeviceCommon`](internal_.DeviceCommon.md)\>

#### Defined in

[types-dev/objects.d.ts:943](https://github.com/ioBroker/ioBroker.js-controller/blob/610f8794837c90e96c314dec3a8f4af930e84d94/packages/types-dev/objects.d.ts#L943)

___

### enums

• `Optional` **enums**: `Record`\<`string`, `string` \| [`Translated`](../modules/internal_.md#translated)\>

#### Inherited from

Partial.enums

#### Defined in

[types-dev/objects.d.ts:907](https://github.com/ioBroker/ioBroker.js-controller/blob/610f8794837c90e96c314dec3a8f4af930e84d94/packages/types-dev/objects.d.ts#L907)

___

### from

• `Optional` **from**: `string`

#### Inherited from

Partial.from

#### Defined in

[types-dev/objects.d.ts:909](https://github.com/ioBroker/ioBroker.js-controller/blob/610f8794837c90e96c314dec3a8f4af930e84d94/packages/types-dev/objects.d.ts#L909)

___

### native

• `Optional` **native**: `Record`\<`string`, `any`\>

#### Inherited from

Partial.native

#### Defined in

[types-dev/objects.d.ts:905](https://github.com/ioBroker/ioBroker.js-controller/blob/610f8794837c90e96c314dec3a8f4af930e84d94/packages/types-dev/objects.d.ts#L905)

___

### nonEdit

• `Optional` **nonEdit**: [`NonEditable`](internal_.NonEditable.md)

These properties can only be edited if the correct password is provided

#### Inherited from

Partial.nonEdit

#### Defined in

[types-dev/objects.d.ts:914](https://github.com/ioBroker/ioBroker.js-controller/blob/610f8794837c90e96c314dec3a8f4af930e84d94/packages/types-dev/objects.d.ts#L914)

___

### ts

• `Optional` **ts**: `number`

#### Inherited from

Partial.ts

#### Defined in

[types-dev/objects.d.ts:912](https://github.com/ioBroker/ioBroker.js-controller/blob/610f8794837c90e96c314dec3a8f4af930e84d94/packages/types-dev/objects.d.ts#L912)

___

### type

• `Optional` **type**: ``"device"``

#### Inherited from

Partial.type

#### Defined in

[types-dev/objects.d.ts:938](https://github.com/ioBroker/ioBroker.js-controller/blob/610f8794837c90e96c314dec3a8f4af930e84d94/packages/types-dev/objects.d.ts#L938)

___

### user

• `Optional` **user**: `string`

The user who created or updated this object

#### Inherited from

Partial.user

#### Defined in

[types-dev/objects.d.ts:911](https://github.com/ioBroker/ioBroker.js-controller/blob/610f8794837c90e96c314dec3a8f4af930e84d94/packages/types-dev/objects.d.ts#L911)
