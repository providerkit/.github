<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/providerkit/.github/main/profile/banner-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/providerkit/.github/main/profile/banner-light.svg">
    <img alt="providerkit" src="https://raw.githubusercontent.com/providerkit/.github/main/profile/banner-light.svg" width="100%">
  </picture>
</p>

<p align="center"><sub>English · <a href="https://github.com/providerkit/.github/blob/main/profile/README.pt-BR.md">Português</a> · <a href="https://github.com/providerkit/.github/blob/main/profile/README.es.md">Español</a></sub></p>

[providerkit](https://github.com/providerkit/providerkit) lets you call AI models from TypeScript without rewriting your code for each provider. You keep control of what your agent does.

- Detect responses that stop arriving, and decide when to retry or switch models.
- Tell temporary failures apart from account limits and conversations that are too long.
- Read usage and cost in the same format across providers.

No extra packages needed to run it. Works in Node 22+, Bun, Deno, Cloudflare Workers and Chrome extensions.

```sh
bun add @providerkit/core
```

[Get started](https://providerkit.dev/guides/getting-started/) · [Documentation](https://providerkit.dev) · [npm](https://www.npmjs.com/package/@providerkit/core)
