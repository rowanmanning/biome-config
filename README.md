
# Biome Config

Shared [Biome](https://biomejs.dev/) linting/formatting configurations for my projects.

* [Requirements](#requirements)
* [Usage](#usage)
* [Contributing](#contributing)
* [License](#license)


## Requirements

This library requires the following to run:

  * [Node.js](https://nodejs.org/) 18+


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


## Contributing

Genuinely unless you're Rowan Manning, you probably don't need to contribute to this. However, if you decide you really need to, then [the contributing guide is available here](docs/contributing.md). All contributors must follow [this library's code of conduct](docs/code_of_conduct.md).


## License

Licensed under the [MIT](LICENSE) license.<br/>
Copyright &copy; 2024, Rowan Manning
