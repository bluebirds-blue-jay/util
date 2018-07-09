# Utils

[![npm](https://img.shields.io/npm/v/@bluejay/utils.svg?style=flat-square)](https://www.npmjs.com/package/@bluejay/utils)
 [![npm](https://img.shields.io/npm/dm/@bluejay/utils.svg?style=flat-square)](https://www.npmjs.com/package/@bluejay/utils)
[![npm](https://img.shields.io/npm/l/@bluejay/utils.svg?style=flat-square)](https://www.npmjs.com/package/@bluejay/utils)

General purpose utilities for Bluejay modules.

## Requirements

- `node >= 7.10`
- `typescript >= 2.4`

## Installation

`npm i @bluejay/utils [--save]`

## Usage

```typescript
import * as Utils from '@bluejay/utils';

Utils.makeArray(1); // [1]
```

Using the name export.

```typescript
import { Utils } from '@bluejay/utils';

Utils.makeArray(1); // [1]
```

Or directly.

```typescript
import { makeArray } from '@bluejay/utils';

makeArray(1); // [1]
```

## Documentation

See [Github Pages](https://bluebirds-blue-jay.github.io/utils/).
