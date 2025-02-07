# Nuxt4 Minimal Starter

This barebones starter simply integrates the [Testing Nuxt 4](https://nuxt.com/docs/getting-started/upgrade#testing-nuxt-4) upgrade guide.

Check also A.Lichter's video on [how to already use Nuxt 4](https://www.youtube.com/watch?v=r4wFKlcJK6c).

Look at the [Nuxt documentation](https://nuxt.com/docs/getting-started/introduction) to learn more.

## New folders structure

The v4 will introduce a new folders structure:

```bash
.output/
.nuxt/
app/
  assets/
  components/
  composables/
  layouts/
  middleware/
  pages/
  plugins/
  utils/
  app.config.ts
  app.vue
  router.options.ts
content/
layers/
modules/
node_modules/
public/
server/
  api/
  middleware/
  plugins/
  routes/
  utils/
nuxt.config.ts
```

All that this starter does, is addind by default the `future` section to the `nuxt.config.ts`.

```ts
future: {
  compatibilityVersion: 4,
}
```

With that in place, we can use the new folders structure and more. Read the NuxtDocs for up to date information.

The intent of this starter is to be a simple template for new Nuxt4 projects.


--- The rest of the README is unchanged ---

The base of that repo was simply a nuxi call, 
with the v4 flag on-top.

## Setup

Make sure to install dependencies:

```bash
# npm
npm install

# pnpm
pnpm install

# yarn
yarn install

# bun
bun install
```

## Development Server

Start the development server on `http://localhost:3000`:

```bash
# npm
npm run dev

# pnpm
pnpm dev

# yarn
yarn dev

# bun
bun run dev
```

## Production

Build the application for production:

```bash
# npm
npm run build

# pnpm
pnpm build

# yarn
yarn build

# bun
bun run build
```

Locally preview production build:

```bash
# npm
npm run preview

# pnpm
pnpm preview

# yarn
yarn preview

# bun
bun run preview
```


