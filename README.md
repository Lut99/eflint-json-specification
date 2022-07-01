# eFLINT JSON Specification
This repository contains examples and releases for the eFLINT JSON Specification. This is a formalization of the communication with an [eFLINT](https://gitlab.com/eflint) reasoner that acts as a server.


## Structure
This repository is structured as follows.

Its main files and folder contains various examples that show the mapping between various snippets of eFLINT and their JSON counterparts. Among these is the running example found in the specification itself, but then restructure to be a large, coherent eFLINT file.

The specification itself can be found under the [releases](https://github.com/Lut99/eflint-json-specification/releases) tab.


## Running the examples
To run the examples, you need to install an eFLINT reasoner first. Currently, the best choice would be the already existing [Haskell](https://www.haskell.org/) implementation (found [here](https://gitlab.com/eflint/haskell-implementation)).

Once installed, you can navigate to each of the folders to run the files.

To run the eFLINT file, use:
```bash
eflint-repl ./<filename>.eflint
```

You can then run the matching JSON file to check if they produce identical output:
```bash
# TODO
```


## Contribution
If you want to contribute to this project, feel free to drop a [pull request](https://github.com/Lut99/eflint-json-specification/pulls) or [raise an issue](https://github.com/Lut99/eflint-json-specification/issues).

