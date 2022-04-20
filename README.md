# [name]

[![NPM version](https://img.shields.io/npm/v/[name].svg)](https://npmjs.org/package/[name])

## How to use this template?

### Github Template

Click use this template

### Clone to local

```bash
npx degit Dunqing/vite-plugin-starter vite-plugin-name

cd vite-plugin-name

pnpm i
```

Then, replace all [name] with your package name




## Install

```bash
pnpm add [name] -D
```

## Usage

```typescript
import { defineConfig } from 'vite'
import importDynamicModule from '[name]'

export default defineConfig({
  plugins: [importDynamicModule()],
})
```


### Options

#### `include`

Type: `string` | `Array<string>`<br>
Default: `[]`

Files to include in this plugin (default all).

#### `exclude`

Type: `string` | `Array<string>`<br>
Default: `[]`

Files to exclude in this plugin (default none).

[LICENSE (MIT)](/LICENSE)