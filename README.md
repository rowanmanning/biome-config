
# Biome Config

Shared [Biome](https://biomejs.dev/) linting/formatting configurations for my projects.

* [Requirements](#requirements)
* [Usage](#usage)
* [Migration](#migration)
* [Contributing](#contributing)
* [License](#license)


## Requirements

This library requires the following to run:

  * [Node.js](https://nodejs.org/) 22+


## Usage

Install with [npm](https://www.npmjs.com/) (`biome` will be included):

```sh
npm install --save-dev @rowanmanning/biome-config
```

Add this to your `biome.json` file:

```json
{
    "$schema": "./node_modules/@biomejs/biome/configuration_schema.json",
    "extends": ["./node_modules/@rowanmanning/biome-config/config.json"]
}
```


## Migration

A new major version of this project is released if breaking changes are introduced. We maintain a [migration guide](docs/migration.md) to help users migrate between these versions.


## Contributing

Genuinely unless you're Rowan Manning, you probably don't need to contribute to this. However, if you decide you really need to, then [the contributing guide is available here](docs/contributing.md). All contributors must follow [this library's code of conduct](docs/code_of_conduct.md).


## License

Licensed under the [MIT](LICENSE) license.<br/>
Copyright &copy; 2024, Rowan Manning
