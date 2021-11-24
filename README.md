<div align="center">

# asdf-kubescape [![Build](https://github.com/juusujanar/asdf-kubescape/actions/workflows/build.yml/badge.svg)](https://github.com/juusujanar/asdf-kubescape/actions/workflows/build.yml) [![Lint](https://github.com/juusujanar/asdf-kubescape/actions/workflows/lint.yml/badge.svg)](https://github.com/juusujanar/asdf-kubescape/actions/workflows/lint.yml)


[kubescape](https://github.com/armosec/kubescape) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add kubescape
# or
asdf plugin add kubescape https://github.com/juusujanar/asdf-kubescape.git
```

kubescape:

```shell
# Show all installable versions
asdf list-all kubescape

# Install specific version
asdf install kubescape latest

# Set a version globally (on your ~/.tool-versions file)
asdf global kubescape latest

# Now kubescape commands are available
kubescape version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/juusujanar/asdf-kubescape/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Janar Juusu](https://github.com/juusujanar/)
