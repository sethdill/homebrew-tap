# Rewrap Markdown Homebrew tap

Install the Rewrap Markdown CLI:

```sh
brew install sethdill/tap/rewrap-markdown
rewrap-markdown --version
```

The formula builds from a checksummed source archive. It installs the CLI and
its license files. The upstream project provides the BBEdit integrations and
Git hook separately.

The tap tests native Apple Silicon and Intel macOS and x86_64 and ARM64 Linux
on GitHub Actions. Intel macOS is covered by this project's matrix. Homebrew's
platform support and package availability may differ. macOS source builds
require Xcode 15 or later. On Linux the formula uses Homebrew Swift as a build
and runtime dependency.

```sh
brew update
brew upgrade rewrap-markdown
brew uninstall rewrap-markdown
```

See the [upstream project](https://github.com/sethdill/rewrap_markdown) for usage
and [report issues upstream](https://github.com/sethdill/rewrap_markdown/issues).
