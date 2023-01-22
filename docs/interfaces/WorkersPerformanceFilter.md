[@zeldafan0225/stable_horde](../README.md) / [Exports](../modules.md) / WorkersPerformanceFilter

# Interface: WorkersPerformanceFilter

## Table of contents

### Properties

- [img2img](WorkersPerformanceFilter.md#img2img)
- [models](WorkersPerformanceFilter.md#models)
- [performance](WorkersPerformanceFilter.md#performance)
- [size](WorkersPerformanceFilter.md#size)

## Properties

### img2img

• `Optional` **img2img**: `boolean`

Worker should support img2img

#### Defined in

[index.ts:1990](https://github.com/ZeldaFan0225/stable_horde/blob/bf3b9d2/index.ts#L1990)

___

### models

• `Optional` **models**: `string`[]

List of models workers should have (at least one)

#### Defined in

[index.ts:1994](https://github.com/ZeldaFan0225/stable_horde/blob/bf3b9d2/index.ts#L1994)

___

### performance

• `Optional` **performance**: `number`

Minimal value of performance for worker to have

**`Default`**

1.5

#### Defined in

[index.ts:1981](https://github.com/ZeldaFan0225/stable_horde/blob/bf3b9d2/index.ts#L1981)

___

### size

• `Optional` **size**: `number`

Minimal filtered workers amount to resort to the list of first `minLength` workers sorted by `performance` value

**`Default`**

5

#### Defined in

[index.ts:1986](https://github.com/ZeldaFan0225/stable_horde/blob/bf3b9d2/index.ts#L1986)