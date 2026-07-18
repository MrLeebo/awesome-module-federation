# Awesome Module Federation [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of resources about learning and using module federation in webpack

## Contents

- [Documentation](#documentation)
- [Git Repositories](#git-repositories)
- [Blogs](#blogs)
- [Videos](#videos)
- [Plugins](#plugins)

## Documentation

- [Module Federation 2.0 Announcement](https://module-federation.io/blog/announcement.html)
- [Module Federation Docs](https://webpack.js.org/concepts/module-federation/)
- [Module Federation 2.0 Guide](https://module-federation.io/guide/start/quick-start.html)
- [Rspack Module Federation Docs](https://rspack.dev/guide/features/module-federation)

## Git Repositories

- [Module Federation Examples](https://github.com/module-federation/module-federation-examples)
- [module-federation/core](https://github.com/module-federation/core) - The MF 2.0 monorepo containing all official packages for Webpack, Rspack, Rsbuild, Vite, Rollup, and Metro
- [module-federation/vite](https://github.com/module-federation/vite) - Official Module Federation plugin for Vite, supporting 13+ frameworks
- [callstack/repack](https://github.com/callstack/repack) - Rspack/Webpack-powered React Native bundler with built-in Module Federation support for mobile micro-frontends

## Blogs

- [Understanding Webpack Module Federation: A Deep Dive](https://medium.com/@scriptedalchemy/understanding-webpack-module-federation-a-deep-dive-efe5c55bf366)
- [Micro-FEs Simplified](https://medium.com/gitconnected/micro-fes-simplified-361dff983c27)
- [Module Federation 2.0 Stable Release](https://module-federation.io/blog/v2-stable-version.html)
- [Error Handling for Remote Module Rendering](https://module-federation.io/blog/error-load-remote.html)
- [Node.js Module Federation](https://module-federation.io/blog/node.html)

## Videos

- [Micro-Frontends in Just 10 minutes](https://www.youtube.com/watch?v=s_Fs4AXsTnA&list=PLNqp92_EXZBLr7p7hn6IYa1YPNs4yJ1t1&index=5)
- [Module Federation - Shared App Shell, State, Routing and Components](https://www.youtube.com/watch?v=-LNcpralkjM)

## Plugins

Additional packages that can enhance your module federation implementation

- [vite-plugin-federation](https://github.com/originjs/vite-plugin-federation)
- [native-federation-typescript](https://github.com/module-federation/core/tree/main/packages/native-federation-typescript)
- [react-singleton-context](https://github.com/indeedeng/react-singleton-context)
- [@module-federation/enhanced](https://github.com/module-federation/core/tree/main/packages/enhanced) - Drop-in replacement for webpack's `ModuleFederationPlugin` with MF 2.0 features: manifest, dynamic TypeScript types, and a runtime plugin system
- [@module-federation/runtime](https://github.com/module-federation/core/tree/main/packages/runtime) - Standalone runtime library for module federation without any build plugin; use `createInstance()` and `loadRemote()` programmatically
- [@module-federation/rsbuild-plugin](https://github.com/module-federation/core/tree/main/packages/rsbuild-plugin) - Official Module Federation integration for Rsbuild, Rslib, and Rspress
- [@module-federation/node](https://github.com/module-federation/core/tree/main/packages/node) - Brings Module Federation to the Node.js runtime for SSR, BFF, and microservices
- [@module-federation/bridge-react](https://github.com/module-federation/core/tree/main/packages/bridge/bridge-react) - Consume remote micro-frontends as fully isolated React applications with their own router and store
- [@module-federation/esbuild](https://github.com/module-federation/core/tree/main/packages/esbuild) - Module Federation plugin for ESBuild
- [@module-federation/storybook-addon](https://github.com/module-federation/core/tree/main/packages/storybook-addon) - Storybook addon for previewing and testing remote Module Federated components in isolation
- [@module-federation/retry-plugin](https://github.com/module-federation/core/tree/main/packages/retry-plugin) - Runtime plugin providing automatic retry with CDN domain rotation for failed remote fetches
- [create-module-federation](https://github.com/module-federation/core/tree/main/packages/create-module-federation) - Official scaffolding CLI to bootstrap new MF 2.0 projects (`npm create module-federation@latest`)

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
