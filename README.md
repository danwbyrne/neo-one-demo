# Prerelease-alpha.4 compile command demo

See https://github.com/neo-one-suite/neo-one/pull/2071 for more information about this functionality.

### How To Start

```
yarn install
yarn neo-one compile

```

### Functionality
You can change the output format using various flags. By default the compiler will output the `json` format contract/abi.
Flags:
  1. `--json` true by default, set to `false` to disable this output type.
  2. `--avm` false by default, pass this flag to enable `avm` file output. If you would like `avm` and `json` output types pass both flags.
  3. `--debug` false by default, pass this flag to enable debug output. This will be `<contract>.debug.json` in the `json` format, and `<contract>.avmdbgnfo` in the `avm` format.
  4. `--abi` true by default, set to `false` to disable outputting a `<contract>.abi.json` file.
