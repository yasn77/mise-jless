<div align="center">

# mise-jless [![Build](https://github.com/yasn77/mise-jless/actions/workflows/build.yml/badge.svg)](https://github.com/yasn77/mise-jless/actions/workflows/build.yml) [![Lint](https://github.com/yasn77/mise-jless/actions/workflows/lint.yml/badge.svg)](https://github.com/yasn77/mise-jless/actions/workflows/lint.yml)

[jless](https://jless.io/) plugin for the [mise version manager](https://mise.jdx.dev/).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `zip`, `awk`: generic POSIX utilities.

# Install

Plugin:

```shell
mise plugin install jless
# or
mise plugin install jless https://github.com/yasn77/mise-jless.git
```

jless:

```shell
# Show all installable versions
mise ls-remote jless

# Install specific version
mise install jless@<VERSION>

# Set a version globally (on your ~/.tool-versions file)
mise global jless@<VERSION>

# Now jless commands are available
jless -V
```

Check [mise getting started](https://mise.jdx.dev/getting-started.html) for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/yasn77/mise-jless/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Yasser Saleemi](https://github.com/yasn77/)
