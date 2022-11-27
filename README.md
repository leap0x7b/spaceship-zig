<h1 align="center">
  ⚡ + 🚀
  <br>Spaceship Zig<br>
</h1>

<h4 align="center">
  A <a href="https://ziglang.org" target="_blank">Zig</a> section for Spaceship prompt
</h4>

<p align="center">
  <a href="https://github.com/leap0x7b/spaceship-zig/releases">
    <img src="https://img.shields.io/github/v/release/leap0x7b/spaceship-zig.svg?style=flat-square"
      alt="GitHub Release" />
  </a>

  <a href="https://github.com/leap0x7b/spaceship-zig/actions">
    <img src="https://img.shields.io/github/workflow/status/leap0x7b/spaceship-zig/ci?style=flat-square"
      alt="GitHub Workflow Status" />
  </a>

  <a href="https://twitter.com/SpaceshipPrompt">
    <img src="https://img.shields.io/badge/twitter-%40SpaceshipPrompt-00ACEE.svg?style=flat-square"
      alt="Spaceship Twitter" />
  </a>

  <a href="https://discord.gg/NTQWz8Dyt9">
    <img
      src="https://img.shields.io/discord/859409950999707668?label=discord&logoColor=white&style=flat-square"
      alt="Chat on Discord"
    />
  </a>
</p>

Current Zig version, through zig (`⚡`).

## Installing

You need to source this plugin somewhere in your dotfiles. Here's how to do it with some popular tools:

### [Oh-My-Zsh]

Execute this command to clone this repo into Oh-My-Zsh plugin's folder:

```zsh
git clone https://github.com/leap0x7b/spaceship-zig.git $ZSH_CUSTOM/plugins/spaceship-zig
```

Include `spaceship-zig` in Oh-My-Zsh plugins list:

```zsh
plugins=($plugins spaceship-zig)
```

### [zplug]

```zsh
zplug "leap0x7b/spaceship-zig"
```

### [antigen]

```zsh
antigen bundle "leap0x7b/spaceship-zig"
```

### [antibody]

```zsh
antibody bundle "leap0x7b/spaceship-zig"
```

### [zinit]

```zsh
zinit light "leap0x7b/spaceship-zig"
```

### [zgen]

```zsh
zgen load "leap0x7b/spaceship-zig"
```

### [sheldon]

```toml
[plugins.spaceship-zig]
github = "leap0x7b/spaceship-zig"
```

### Manual

If none of the above methods works for you, you can install Spaceship manually.

1. Clone this repo somewhere, for example to `$HOME/.zsh/spaceship-zig`.
2. Source this section in your `~/.zshrc`.

### Example

```zsh
mkdir -p "$HOME/.zsh"
git clone --depth=1 https://github.com/leap0x7b/spaceship-zig.git "$HOME/.zsh/spaceship-zig"
```

For initializing prompt system add this to your `.zshrc`:

```zsh title=".zshrc"
source "~/.zsh/spaceship-zig/spaceship-zig.plugin.zsh"
```

## Usage

After installing, add the following line to your `.zshrc` in order to include Ember section in the prompt:

```zsh
spaceship add zig
```

## Options

This section is shown only in directories within a zig context.

| Variable               |              Default               | Meaning                              |
| :--------------------- | :--------------------------------: | ------------------------------------ |
| `SPACESHIP_ZIG_SHOW`   |               `true`               | Show current section                 |
| `SPACESHIP_ZIG_PREFIX` | `$SPACESHIP_PROMPT_DEFAULT_PREFIX` | Prefix before section                |
| `SPACESHIP_ZIG_SUFFIX` | `$SPACESHIP_PROMPT_DEFAULT_SUFFIX` | Suffix after section                 |
| `SPACESHIP_ZIG_SYMBOL` |               `⚡·`                | Character to be shown before version |
| `SPACESHIP_ZIG_COLOR`  |             `yellow`               | Color of section                     |

## Contributing

First, thanks for your interest in contributing!

Contribute to this repo by submitting a pull request. Please use [conventional commits](https://www.conventionalcommits.org/), since this project adheres to [semver](https://semver.org/) and is automatically released via [semantic-release](https://github.com/semantic-release/semantic-release).

## License

MIT © leap123

<!-- References -->

[Oh-My-Zsh]: https://ohmyz.sh/
[zplug]: https://github.com/zplug/zplug
[antigen]: https://antigen.sharats.me/
[antibody]: https://getantibody.github.io/
[zinit]: https://github.com/zdharma/zinit
[zgen]: https://github.com/tarjoilija/zgen
[sheldon]: https://sheldon.cli.rs/
