<div align="center">

# asdf-tcl [![Build](https://github.com/mdekstrand/asdf-tcl/actions/workflows/build.yml/badge.svg)](https://github.com/mdekstrand/asdf-tcl/actions/workflows/build.yml) [![Lint](https://github.com/mdekstrand/asdf-tcl/actions/workflows/lint.yml/badge.svg)](https://github.com/mdekstrand/asdf-tcl/actions/workflows/lint.yml)


[tcl](https://www.tcl.tk/doc/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add tcl
# or
asdf plugin add tcl https://github.com/mdekstrand/asdf-tcl.git
```

tcl:

```shell
# Show all installable versions
asdf list-all tcl

# Install specific version
asdf install tcl latest

# Set a version globally (on your ~/.tool-versions file)
asdf global tcl latest

# Now tcl commands are available
tclsh -version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/mdekstrand/asdf-tcl/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Michael Ekstrand](https://github.com/mdekstrand/)
