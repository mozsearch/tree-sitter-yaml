# tree-sitter-yaml

[![CI][ci]](https://github.com/tree-sitter-grammars/tree-sitter-yaml/actions)
[![discord][discord]](https://discord.gg/w7nTvsVJhm)
[![matrix][matrix]](https://matrix.to/#/#tree-sitter-chat:matrix.org)
[![npm][npm]](https://www.npmjs.com/package/@tree-sitter-grammars/tree-sitter-yaml)
[![crates][crates]](https://crates.io/crates/tree-sitter-yaml)
[![pypi][pypi]](https://pypi.org/project/tree-sitter-yaml/)

A tree-sitter parser for YAML files.

This is [searchfox](https://searchfox.org/)'s fork, whose scanner keeps rows
in 32 bits so that files of more than 32767 lines parse (ex: Firefox's
dom/base/use_counter_metrics.yaml).

## References

- [YAML version 1.2](https://yaml.org/spec/1.2.2/)

[ci]: https://img.shields.io/github/actions/workflow/status/tree-sitter-grammars/tree-sitter-yaml/ci.yml?logo=github&label=CI
[discord]: https://img.shields.io/discord/1063097320771698699?logo=discord&label=discord
[matrix]: https://img.shields.io/matrix/tree-sitter-chat%3Amatrix.org?logo=matrix&label=matrix
[npm]: https://img.shields.io/npm/v/%40tree-sitter-grammars%2Ftree-sitter-yaml?logo=npm
[crates]: https://img.shields.io/crates/v/tree-sitter-yaml?logo=rust
[pypi]: https://img.shields.io/pypi/v/tree-sitter-yaml?logo=pypi&logoColor=ffd242
