# sanity-plugin-supabase-storage

> This is a **Sanity Studio v3** plugin.

## Installation

```sh
npm install sanity-plugin-supabase-storage
```

## Usage

Add it as a plugin in `sanity.config.ts` (or .js):

```ts
import {defineConfig} from 'sanity'
import {myPlugin} from 'sanity-plugin-supabase-storage'

export default defineConfig({
  //...
  plugins: [myPlugin({})],
})
```

## License

[MIT](LICENSE) © zvitez

## Develop & test

This plugin uses [@sanity/plugin-kit](https://github.com/sanity-io/plugin-kit)
with default configuration for build & watch scripts.

See [Testing a plugin in Sanity Studio](https://github.com/sanity-io/plugin-kit#testing-a-plugin-in-sanity-studio)
on how to run this plugin with hotreload in the studio.
