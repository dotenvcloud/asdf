# asdf-dotenv

[DotEnv CLI](https://dotenv.cloud) plugin for [asdf](https://asdf-vm.com) version manager.

## Install

```bash
asdf plugin add dotenv https://github.com/lostlink/dotenv-asdf.git
```

## Use

```bash
# List all available versions
asdf list all dotenv

# Install a specific version
asdf install dotenv 1.0.0

# Set a version globally
asdf global dotenv 1.0.0

# Set a version locally
asdf local dotenv 1.0.0

# Show current version
asdf current dotenv
```

## License

MIT - See [LICENSE](LICENSE) file