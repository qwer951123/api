[Polkadot JS API](../README.md) › [Globals](../globals.md) › ["packages/metadata/src/Metadata/Metadata"](../modules/_packages_metadata_src_metadata_metadata_.md) › [Metadata](_packages_metadata_src_metadata_metadata_.metadata.md)

# Class: Metadata ‹**S, T, V, E**›

**`name`** Metadata

**`description`** 
The versioned runtime metadata as a decoded structure

## Type parameters

▪ **S**: *TypesDef*

▪ **T**: *object*

▪ **V**: *object*

▪ **E**: *object*

## Hierarchy

  ↳ [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md)

  ↳ **Metadata**

## Implements

* Codec

## Index

### Constructors

* [constructor](_packages_metadata_src_metadata_metadata_.metadata.md#constructor)

### Properties

* [registry](_packages_metadata_src_metadata_metadata_.metadata.md#readonly-registry)
* [size](_packages_metadata_src_metadata_metadata_.metadata.md#readonly-size)

### Accessors

* [Type](_packages_metadata_src_metadata_metadata_.metadata.md#type)
* [asCallsOnly](_packages_metadata_src_metadata_metadata_.metadata.md#ascallsonly)
* [asLatest](_packages_metadata_src_metadata_metadata_.metadata.md#aslatest)
* [asV0](_packages_metadata_src_metadata_metadata_.metadata.md#asv0)
* [asV1](_packages_metadata_src_metadata_metadata_.metadata.md#asv1)
* [asV10](_packages_metadata_src_metadata_metadata_.metadata.md#asv10)
* [asV11](_packages_metadata_src_metadata_metadata_.metadata.md#asv11)
* [asV2](_packages_metadata_src_metadata_metadata_.metadata.md#asv2)
* [asV3](_packages_metadata_src_metadata_metadata_.metadata.md#asv3)
* [asV4](_packages_metadata_src_metadata_metadata_.metadata.md#asv4)
* [asV5](_packages_metadata_src_metadata_metadata_.metadata.md#asv5)
* [asV6](_packages_metadata_src_metadata_metadata_.metadata.md#asv6)
* [asV7](_packages_metadata_src_metadata_metadata_.metadata.md#asv7)
* [asV8](_packages_metadata_src_metadata_metadata_.metadata.md#asv8)
* [asV9](_packages_metadata_src_metadata_metadata_.metadata.md#asv9)
* [defKeys](_packages_metadata_src_metadata_metadata_.metadata.md#defkeys)
* [encodedLength](_packages_metadata_src_metadata_metadata_.metadata.md#encodedlength)
* [hash](_packages_metadata_src_metadata_metadata_.metadata.md#hash)
* [isEmpty](_packages_metadata_src_metadata_metadata_.metadata.md#isempty)
* [magicNumber](_packages_metadata_src_metadata_metadata_.metadata.md#magicnumber)
* [version](_packages_metadata_src_metadata_metadata_.metadata.md#version)

### Methods

* [clear](_packages_metadata_src_metadata_metadata_.metadata.md#clear)
* [delete](_packages_metadata_src_metadata_metadata_.metadata.md#delete)
* [eq](_packages_metadata_src_metadata_metadata_.metadata.md#eq)
* [forEach](_packages_metadata_src_metadata_metadata_.metadata.md#foreach)
* [get](_packages_metadata_src_metadata_metadata_.metadata.md#get)
* [getAtIndex](_packages_metadata_src_metadata_metadata_.metadata.md#getatindex)
* [getUniqTypes](_packages_metadata_src_metadata_metadata_.metadata.md#getuniqtypes)
* [has](_packages_metadata_src_metadata_metadata_.metadata.md#has)
* [set](_packages_metadata_src_metadata_metadata_.metadata.md#set)
* [toArray](_packages_metadata_src_metadata_metadata_.metadata.md#toarray)
* [toHex](_packages_metadata_src_metadata_metadata_.metadata.md#tohex)
* [toHuman](_packages_metadata_src_metadata_metadata_.metadata.md#tohuman)
* [toJSON](_packages_metadata_src_metadata_metadata_.metadata.md#tojson)
* [toRawType](_packages_metadata_src_metadata_metadata_.metadata.md#torawtype)
* [toString](_packages_metadata_src_metadata_metadata_.metadata.md#tostring)
* [toU8a](_packages_metadata_src_metadata_metadata_.metadata.md#tou8a)
* [typesToMap](_packages_metadata_src_metadata_metadata_.metadata.md#static-typestomap)
* [with](_packages_metadata_src_metadata_metadata_.metadata.md#static-with)

## Constructors

###  constructor

\+ **new Metadata**(`registry`: Registry, `value?`: Uint8Array | string): *[Metadata](_packages_metadata_src_metadata_metadata_.metadata.md)*

*Overrides [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[constructor](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#constructor)*

*Defined in [packages/metadata/src/Metadata/Metadata.ts:43](https://github.com/polkadot-js/api/blob/eb6b3c5bd4/packages/metadata/src/Metadata/Metadata.ts#L43)*

**Parameters:**

Name | Type |
------ | ------ |
`registry` | Registry |
`value?` | Uint8Array &#124; string |

**Returns:** *[Metadata](_packages_metadata_src_metadata_metadata_.metadata.md)*

## Properties

### `Readonly` registry

• **registry**: *Registry*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[registry](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#readonly-registry)*

*Defined in [packages/types/src/codec/Struct.ts:111](https://github.com/polkadot-js/api/blob/eb6b3c5bd4/packages/types/src/codec/Struct.ts#L111)*

___

### `Readonly` size

• **size**: *number*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[size](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#readonly-size)*

Defined in node_modules/typescript/lib/lib.es2015.collection.d.ts:28

## Accessors

###  Type

• **get Type**(): *E*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[Type](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#type)*

*Defined in [packages/types/src/codec/Struct.ts:174](https://github.com/polkadot-js/api/blob/eb6b3c5bd4/packages/types/src/codec/Struct.ts#L174)*

**`description`** Returns the Type description to sthe structure

**Returns:** *E*

___

###  asCallsOnly

• **get asCallsOnly**(): *[MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md)*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[asCallsOnly](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#ascallsonly)*

*Defined in [packages/metadata/src/Metadata/MetadataVersioned.ts:71](https://github.com/polkadot-js/api/blob/eb6b3c5bd4/packages/metadata/src/Metadata/MetadataVersioned.ts#L71)*

**`description`** Returns the wrapped metadata as a limited calls-only (latest) version

**Returns:** *[MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md)*

___

###  asLatest

• **get asLatest**(): *MetadataLatest*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[asLatest](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#aslatest)*

*Defined in [packages/metadata/src/Metadata/MetadataVersioned.ts:167](https://github.com/polkadot-js/api/blob/eb6b3c5bd4/packages/metadata/src/Metadata/MetadataVersioned.ts#L167)*

**`description`** Returns the wrapped values as a latest version object

**Returns:** *MetadataLatest*

___

###  asV0

• **get asV0**(): *MetadataV0*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[asV0](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#asv0)*

*Defined in [packages/metadata/src/Metadata/MetadataVersioned.ts:81](https://github.com/polkadot-js/api/blob/eb6b3c5bd4/packages/metadata/src/Metadata/MetadataVersioned.ts#L81)*

**`description`** Returns the wrapped metadata as a V0 object

**Returns:** *MetadataV0*

___

###  asV1

• **get asV1**(): *MetadataV1*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[asV1](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#asv1)*

*Defined in [packages/metadata/src/Metadata/MetadataVersioned.ts:90](https://github.com/polkadot-js/api/blob/eb6b3c5bd4/packages/metadata/src/Metadata/MetadataVersioned.ts#L90)*

**`description`** Returns the wrapped values as a V1 object

**Returns:** *MetadataV1*

___

###  asV10

• **get asV10**(): *MetadataV10*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[asV10](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#asv10)*

*Defined in [packages/metadata/src/Metadata/MetadataVersioned.ts:153](https://github.com/polkadot-js/api/blob/eb6b3c5bd4/packages/metadata/src/Metadata/MetadataVersioned.ts#L153)*

**`description`** Returns the wrapped values as a V10 object

**Returns:** *MetadataV10*

___

###  asV11

• **get asV11**(): *MetadataV11*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[asV11](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#asv11)*

*Defined in [packages/metadata/src/Metadata/MetadataVersioned.ts:160](https://github.com/polkadot-js/api/blob/eb6b3c5bd4/packages/metadata/src/Metadata/MetadataVersioned.ts#L160)*

**`description`** Returns the wrapped values as a V10 object

**Returns:** *MetadataV11*

___

###  asV2

• **get asV2**(): *MetadataV2*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[asV2](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#asv2)*

*Defined in [packages/metadata/src/Metadata/MetadataVersioned.ts:97](https://github.com/polkadot-js/api/blob/eb6b3c5bd4/packages/metadata/src/Metadata/MetadataVersioned.ts#L97)*

**`description`** Returns the wrapped values as a V2 object

**Returns:** *MetadataV2*

___

###  asV3

• **get asV3**(): *MetadataV3*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[asV3](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#asv3)*

*Defined in [packages/metadata/src/Metadata/MetadataVersioned.ts:104](https://github.com/polkadot-js/api/blob/eb6b3c5bd4/packages/metadata/src/Metadata/MetadataVersioned.ts#L104)*

**`description`** Returns the wrapped values as a V3 object

**Returns:** *MetadataV3*

___

###  asV4

• **get asV4**(): *MetadataV4*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[asV4](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#asv4)*

*Defined in [packages/metadata/src/Metadata/MetadataVersioned.ts:111](https://github.com/polkadot-js/api/blob/eb6b3c5bd4/packages/metadata/src/Metadata/MetadataVersioned.ts#L111)*

**`description`** Returns the wrapped values as a V4 object

**Returns:** *MetadataV4*

___

###  asV5

• **get asV5**(): *MetadataV5*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[asV5](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#asv5)*

*Defined in [packages/metadata/src/Metadata/MetadataVersioned.ts:118](https://github.com/polkadot-js/api/blob/eb6b3c5bd4/packages/metadata/src/Metadata/MetadataVersioned.ts#L118)*

**`description`** Returns the wrapped values as a V5 object

**Returns:** *MetadataV5*

___

###  asV6

• **get asV6**(): *MetadataV6*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[asV6](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#asv6)*

*Defined in [packages/metadata/src/Metadata/MetadataVersioned.ts:125](https://github.com/polkadot-js/api/blob/eb6b3c5bd4/packages/metadata/src/Metadata/MetadataVersioned.ts#L125)*

**`description`** Returns the wrapped values as a V6 object

**Returns:** *MetadataV6*

___

###  asV7

• **get asV7**(): *MetadataV7*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[asV7](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#asv7)*

*Defined in [packages/metadata/src/Metadata/MetadataVersioned.ts:132](https://github.com/polkadot-js/api/blob/eb6b3c5bd4/packages/metadata/src/Metadata/MetadataVersioned.ts#L132)*

**`description`** Returns the wrapped values as a V7 object

**Returns:** *MetadataV7*

___

###  asV8

• **get asV8**(): *MetadataV8*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[asV8](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#asv8)*

*Defined in [packages/metadata/src/Metadata/MetadataVersioned.ts:139](https://github.com/polkadot-js/api/blob/eb6b3c5bd4/packages/metadata/src/Metadata/MetadataVersioned.ts#L139)*

**`description`** Returns the wrapped values as a V8 object

**Returns:** *MetadataV8*

___

###  asV9

• **get asV9**(): *MetadataV9*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[asV9](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#asv9)*

*Defined in [packages/metadata/src/Metadata/MetadataVersioned.ts:146](https://github.com/polkadot-js/api/blob/eb6b3c5bd4/packages/metadata/src/Metadata/MetadataVersioned.ts#L146)*

**`description`** Returns the wrapped values as a V9 object

**Returns:** *MetadataV9*

___

###  defKeys

• **get defKeys**(): *string[]*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[defKeys](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#defkeys)*

*Defined in [packages/types/src/codec/Struct.ts:152](https://github.com/polkadot-js/api/blob/eb6b3c5bd4/packages/types/src/codec/Struct.ts#L152)*

**`description`** The available keys for this enum

**Returns:** *string[]*

___

###  encodedLength

• **get encodedLength**(): *number*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[encodedLength](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#encodedlength)*

*Defined in [packages/types/src/codec/Struct.ts:188](https://github.com/polkadot-js/api/blob/eb6b3c5bd4/packages/types/src/codec/Struct.ts#L188)*

**`description`** The length of the value when encoded as a Uint8Array

**Returns:** *number*

___

###  hash

• **get hash**(): *H256*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[hash](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#hash)*

*Defined in [packages/types/src/codec/Struct.ts:199](https://github.com/polkadot-js/api/blob/eb6b3c5bd4/packages/types/src/codec/Struct.ts#L199)*

**`description`** returns a hash of the contents

**Returns:** *H256*

___

###  isEmpty

• **get isEmpty**(): *boolean*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[isEmpty](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#isempty)*

*Defined in [packages/types/src/codec/Struct.ts:159](https://github.com/polkadot-js/api/blob/eb6b3c5bd4/packages/types/src/codec/Struct.ts#L159)*

**`description`** Checks if the value is an empty value

**Returns:** *boolean*

___

###  magicNumber

• **get magicNumber**(): *[MagicNumber](_packages_metadata_src_metadata_magicnumber_.magicnumber.md)*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[magicNumber](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#magicnumber)*

*Defined in [packages/metadata/src/Metadata/MetadataVersioned.ts:175](https://github.com/polkadot-js/api/blob/eb6b3c5bd4/packages/metadata/src/Metadata/MetadataVersioned.ts#L175)*

**`description`** 

**Returns:** *[MagicNumber](_packages_metadata_src_metadata_magicnumber_.magicnumber.md)*

___

###  version

• **get version**(): *number*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[version](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#version)*

*Defined in [packages/metadata/src/Metadata/MetadataVersioned.ts:189](https://github.com/polkadot-js/api/blob/eb6b3c5bd4/packages/metadata/src/Metadata/MetadataVersioned.ts#L189)*

**`description`** the metadata version this structure represents

**Returns:** *number*

## Methods

###  clear

▸ **clear**(): *void*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[clear](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#clear)*

Defined in node_modules/typescript/lib/lib.es2015.collection.d.ts:22

**Returns:** *void*

___

###  delete

▸ **delete**(`key`: keyof S): *boolean*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[delete](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#delete)*

Defined in node_modules/typescript/lib/lib.es2015.collection.d.ts:23

**Parameters:**

Name | Type |
------ | ------ |
`key` | keyof S |

**Returns:** *boolean*

___

###  eq

▸ **eq**(`other?`: unknown): *boolean*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[eq](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#eq)*

*Defined in [packages/types/src/codec/Struct.ts:206](https://github.com/polkadot-js/api/blob/eb6b3c5bd4/packages/types/src/codec/Struct.ts#L206)*

**`description`** Compares the value of the input to see if there is a match

**Parameters:**

Name | Type |
------ | ------ |
`other?` | unknown |

**Returns:** *boolean*

___

###  forEach

▸ **forEach**(`callbackfn`: function, `thisArg?`: any): *void*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[forEach](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#foreach)*

Defined in node_modules/typescript/lib/lib.es2015.collection.d.ts:24

**Parameters:**

▪ **callbackfn**: *function*

▸ (`value`: Codec, `key`: keyof S, `map`: Map‹keyof S, Codec›): *void*

**Parameters:**

Name | Type |
------ | ------ |
`value` | Codec |
`key` | keyof S |
`map` | Map‹keyof S, Codec› |

▪`Optional`  **thisArg**: *any*

**Returns:** *void*

___

###  get

▸ **get**(`name`: keyof S): *Codec | undefined*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[get](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#get)*

*Overrides void*

*Defined in [packages/types/src/codec/Struct.ts:214](https://github.com/polkadot-js/api/blob/eb6b3c5bd4/packages/types/src/codec/Struct.ts#L214)*

**`description`** Returns a specific names entry in the structure

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`name` | keyof S | The name of the entry to retrieve  |

**Returns:** *Codec | undefined*

___

###  getAtIndex

▸ **getAtIndex**(`index`: number): *Codec*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[getAtIndex](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#getatindex)*

*Defined in [packages/types/src/codec/Struct.ts:221](https://github.com/polkadot-js/api/blob/eb6b3c5bd4/packages/types/src/codec/Struct.ts#L221)*

**`description`** Returns the values of a member at a specific index (Rather use get(name) for performance)

**Parameters:**

Name | Type |
------ | ------ |
`index` | number |

**Returns:** *Codec*

___

###  getUniqTypes

▸ **getUniqTypes**(`throwError`: boolean): *string[]*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[getUniqTypes](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#getuniqtypes)*

*Defined in [packages/metadata/src/Metadata/MetadataVersioned.ts:193](https://github.com/polkadot-js/api/blob/eb6b3c5bd4/packages/metadata/src/Metadata/MetadataVersioned.ts#L193)*

**Parameters:**

Name | Type |
------ | ------ |
`throwError` | boolean |

**Returns:** *string[]*

___

###  has

▸ **has**(`key`: keyof S): *boolean*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[has](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#has)*

Defined in node_modules/typescript/lib/lib.es2015.collection.d.ts:26

**Parameters:**

Name | Type |
------ | ------ |
`key` | keyof S |

**Returns:** *boolean*

___

###  set

▸ **set**(`key`: keyof S, `value`: Codec): *this*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[set](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#set)*

Defined in node_modules/typescript/lib/lib.es2015.collection.d.ts:27

**Parameters:**

Name | Type |
------ | ------ |
`key` | keyof S |
`value` | Codec |

**Returns:** *this*

___

###  toArray

▸ **toArray**(): *Codec[]*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[toArray](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#toarray)*

*Defined in [packages/types/src/codec/Struct.ts:228](https://github.com/polkadot-js/api/blob/eb6b3c5bd4/packages/types/src/codec/Struct.ts#L228)*

**`description`** Converts the Object to an standard JavaScript Array

**Returns:** *Codec[]*

___

###  toHex

▸ **toHex**(): *string*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[toHex](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#tohex)*

*Defined in [packages/types/src/codec/Struct.ts:235](https://github.com/polkadot-js/api/blob/eb6b3c5bd4/packages/types/src/codec/Struct.ts#L235)*

**`description`** Returns a hex string representation of the value

**Returns:** *string*

___

###  toHuman

▸ **toHuman**(`isExtended?`: undefined | false | true): *AnyJson*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[toHuman](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#tohuman)*

*Defined in [packages/types/src/codec/Struct.ts:242](https://github.com/polkadot-js/api/blob/eb6b3c5bd4/packages/types/src/codec/Struct.ts#L242)*

**`description`** Converts the Object to to a human-friendly JSON, with additional fields, expansion and formatting of information

**Parameters:**

Name | Type |
------ | ------ |
`isExtended?` | undefined &#124; false &#124; true |

**Returns:** *AnyJson*

___

###  toJSON

▸ **toJSON**(): *AnyJson*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[toJSON](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#tojson)*

*Defined in [packages/types/src/codec/Struct.ts:255](https://github.com/polkadot-js/api/blob/eb6b3c5bd4/packages/types/src/codec/Struct.ts#L255)*

**`description`** Converts the Object to JSON, typically used for RPC transfers

**Returns:** *AnyJson*

___

###  toRawType

▸ **toRawType**(): *string*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[toRawType](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#torawtype)*

*Defined in [packages/types/src/codec/Struct.ts:279](https://github.com/polkadot-js/api/blob/eb6b3c5bd4/packages/types/src/codec/Struct.ts#L279)*

**`description`** Returns the base runtime type name for this instance

**Returns:** *string*

___

###  toString

▸ **toString**(): *string*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[toString](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#tostring)*

*Defined in [packages/types/src/codec/Struct.ts:288](https://github.com/polkadot-js/api/blob/eb6b3c5bd4/packages/types/src/codec/Struct.ts#L288)*

**`description`** Returns the string representation of the value

**Returns:** *string*

___

###  toU8a

▸ **toU8a**(`isBare?`: BareOpts): *Uint8Array*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[toU8a](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#tou8a)*

*Defined in [packages/types/src/codec/Struct.ts:296](https://github.com/polkadot-js/api/blob/eb6b3c5bd4/packages/types/src/codec/Struct.ts#L296)*

**`description`** Encodes the value as a Uint8Array as per the SCALE specifications

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`isBare?` | BareOpts | true when the value has none of the type-specific prefixes (internal)  |

**Returns:** *Uint8Array*

___

### `Static` typesToMap

▸ **typesToMap**(`registry`: Registry, `Types`: Record‹string, Constructor›): *Record‹string, string›*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[typesToMap](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#static-typestomap)*

*Defined in [packages/types/src/codec/Struct.ts:268](https://github.com/polkadot-js/api/blob/eb6b3c5bd4/packages/types/src/codec/Struct.ts#L268)*

**Parameters:**

Name | Type |
------ | ------ |
`registry` | Registry |
`Types` | Record‹string, Constructor› |

**Returns:** *Record‹string, string›*

___

### `Static` with

▸ **with**‹**S**›(`Types`: S, `jsonMap?`: Map‹keyof S, string›): *Constructor‹Struct‹S››*

*Inherited from [MetadataVersioned](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md).[with](_packages_metadata_src_metadata_metadataversioned_.metadataversioned.md#static-with)*

*Defined in [packages/types/src/codec/Struct.ts:128](https://github.com/polkadot-js/api/blob/eb6b3c5bd4/packages/types/src/codec/Struct.ts#L128)*

**Type parameters:**

▪ **S**: *TypesDef*

**Parameters:**

Name | Type |
------ | ------ |
`Types` | S |
`jsonMap?` | Map‹keyof S, string› |

**Returns:** *Constructor‹Struct‹S››*