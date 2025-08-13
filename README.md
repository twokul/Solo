# Shade

Shade is a minimal theme for [Ghost](https://github.com/TryGhost/Ghost) based on [Solo](https://github.com/TryGhost/Solo).

# Development

Edition styles are compiled using Gulp/PostCSS to polyfill future CSS spec. You'll need [Node](https://nodejs.org/), [Yarn](https://yarnpkg.com/) and [Gulp](https://gulpjs.com) installed globally. After that, from the theme's root directory:

```bash
# Install
pnpm install

# Run build & watch for changes
pnpm dev
```

Now you can edit `/assets/css/` files, which will be compiled to `/assets/built/` automatically.

The `zip` Gulp task packages the theme files into `dist/solo.zip`, which you can then upload to your site.

```bash
pnpm zip
```

# Contribution

This repo is synced automatically with [TryGhost/Themes](https://github.com/TryGhost/Themes) monorepo. If you're looking to contribute or raise an issue, head over to the main repository [TryGhost/Themes](https://github.com/TryGhost/Themes) where our official themes are developed.

## Copyright & License

Copyright (c) 2013-2025 Ghost Foundation - Released under the [MIT license](LICENSE).
