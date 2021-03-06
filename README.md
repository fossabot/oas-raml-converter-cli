[![Greenkeeper badge](https://badges.greenkeeper.io/daviemakz/oas-raml-converter-cli.svg)](https://greenkeeper.io/)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fdaviemakz%2Foas-raml-converter-cli.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fdaviemakz%2Foas-raml-converter-cli?ref=badge_shield)

[![NPM](https://nodei.co/npm/oas-raml-converter-cli.png?compact=true)](https://www.npmjs.com/package/oas-raml-converter-cli)

[![Build Status](https://travis-ci.org/daviemakz/oas-raml-converter-cli.svg?branch=master)](https://travis-ci.org/daviemakz/oas-raml-converter-cli)
[![dependencies Status](https://david-dm.org/daviemakz/oas-raml-converter-cli/status.svg)](https://david-dm.org/daviemakz/oas-raml-converter-cli)
[![devDependencies Status](https://david-dm.org/daviemakz/oas-raml-converter-cli/dev-status.svg)](https://david-dm.org/daviemakz/oas-raml-converter-cli?type=dev)

# OAS RAML Converter (CLI)

This package is a CLI wrapper designed to allow conversion between OAS / RAML specifications via a command line interface. This module uses (https://github.com/mulesoft/oas-raml-converter) under the hood so its very reliable. This package works across all platforms and is intended to be used globally.

_Supports Node 6.x +_

## Installation

Install the module globally via Yarn or NPM:

### Yarn

    yarn global add oas-raml-converter-cli

### NPM

    npm install -g oas-raml-converter-cli

## Executing

To run the CLI utility run the following command after installing:

1.  Start the utility via `oasraml-cli` or `oas-raml-converter-cli` in the console and you will see this:

```
Choose the type of converter you want to use (enter option 1-5):

1) RAML 0.8 > RAML 1.0
2) RAML 0.8 > OAS 2.0
3) RAML 1.0 > OAS 2.0
4) RAML 1.0 > OAS 3.0
5) OAS 2.0 > RAML 1.0

Enter now:
```

2.  After choosing your option select the source file (the utility will check if it exists before continuing):

```
Enter the source path of the file:
```

3.  Enter a destination path. If the folders do not exist the application will create them. Ensure you have adequate permissions in your target destination:

```
Enter the destination path for the file:
```

4.  A final prompt before performing the conversion, press (y) to continue or (n) to abort:

```
Are you sure you want to continue (y/n):
```

That’s it! Your file should now be converted. You will be able to convert OAS to RAML and vice versa as many times as you like.

## Test

Run the following commands to test the module:

`yarn install && yarn test`

or

`npm install && npm test`

## Contributing

All contributions are very welcome, please read my [CONTRIBUTING.md](https://github.com/daviemakz/oas-raml-converter-cli/blob/master/CONTRIBUTING.md) first. You can submit any ideas as [pull requests](https://github.com/daviemakz/oas-raml-converter-cli/pulls) or as [GitHub issues](https://github.com/daviemakz/oas-raml-converter-cli/issues). If you'd like to improve code, please feel free!


## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fdaviemakz%2Foas-raml-converter-cli.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fdaviemakz%2Foas-raml-converter-cli?ref=badge_large)