[**@iobroker/js-controller-adapter**](../../README.md) • **Docs**

***

[@iobroker/js-controller-adapter](../../globals.md) / [\<internal\>](../README.md) / LicenseInformationWithPayment

# Interface: LicenseInformationWithPayment

## Properties

### license?

> `optional` **license**: `string`

License of the software

#### Defined in

[types-dev/objects.d.ts:530](https://github.com/ioBroker/ioBroker.js-controller/blob/b50a278725d350a15d2e89556fee6afed5154f0b/packages/types-dev/objects.d.ts#L530)

***

### link

> **link**: `string`

Hyperlink, where information about the license can be found. For non-free licenses, the linked page should contain information about free features (if applicable), time of validity, link to shop and seller information.
This is required if the license type is different from 'free'. For 'free' licenses, an optional link to the license file can be placed here.

#### Defined in

[types-dev/objects.d.ts:537](https://github.com/ioBroker/ioBroker.js-controller/blob/b50a278725d350a15d2e89556fee6afed5154f0b/packages/types-dev/objects.d.ts#L537)

***

### type

> **type**: [`PaidLicenseType`](../type-aliases/PaidLicenseType.md)

Use 'paid' for adapters which do not work without a paid license. Use 'commercial' for adapters which require a license for commercial use only. Use 'limited' if some functionalities are not available without a paid license.

#### Defined in

[types-dev/objects.d.ts:532](https://github.com/ioBroker/ioBroker.js-controller/blob/b50a278725d350a15d2e89556fee6afed5154f0b/packages/types-dev/objects.d.ts#L532)