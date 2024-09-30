# RCLI

## Introduction

This is a command-line tool developed in Rust language, currently supporting the following features:
* CSV conversion to JSON and YAML.
* Random password generation.

## Quick Start
Please open the terminal where the project root directory is located and execute the following command

### CSV
#### Command

```
cargo run csv --input [your csv file path] --format [target file type]
```

#### eg:
```bash
cargo run csv --input assets/juventus.csv  --format yaml
```

### GEN_PASS
#### Command

```bash
cargo run genpass
```

## Tip

You can also use ``--help`` to view the supported parameters and functions

### Command

```
cargo run [option] --help
```

### eg
```bash
cargo run csv --help
```
