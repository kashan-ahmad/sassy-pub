# Sassy Pub

Sassy Pub is a simple boilerplate for creating and publishing packages to NPM. It includes a basic configuration for TypeScript, ESLint, Prettier, and Changesets as well as a simple list of scripts for building, linting, and publishing your package.

## Features

- TypeScript
- ESLint
- Prettier
- Changesets

## Getting Started

To get started with Sassy Pub, simply follow these steps:

1. Clone the Sassy Pub repository to your local machine:

```bash
git clone https://github.com/kashan-ahmad/sassy-pub
```

2. Review the `package.json` file and make any necessary changes to the package name, version, description, and the scripts.
3. Run `npm install` to install the project dependencies.
4. Run `npm run release` to build, lint, format, and publish the project.

Note that the `release` script will automatically bump the package version using changesets, refer to the [changesets documentation](https://github.com/changesets/changesets/blob/main/docs/intro-to-using-changesets.md) for more information.

Also note that the `build` script builds everything to the `dist` directory, which is then published to NPM with the `package.json` and other necessary files copied from the root directory.

## Contributing

We welcome contributions from the community! If you'd like to contribute to Sassy Pub, please read our [contributing guidelines](CONTRIBUTING.md) to get started.

## License

Sassy Pub is open source software released under the [MIT License](LICENSE). We encourage you to use, modify, and distribute Sassy Pub as you see fit.
