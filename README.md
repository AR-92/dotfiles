# dotfiles

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A comprehensive collection of my personal configuration files for a consistent and productive development environment.

## Description

This repository contains my personal configuration files (dotfiles) that I use to set up and maintain a consistent development environment across multiple systems. These configurations help me work more efficiently by providing a familiar and well-tuned environment wherever I work.

## Key Features

- Terminal configuration (bashrc, aliases, prompt customization)
- Vim and other editor settings
- Git configuration and aliases
- Development tool configurations (tmux, ssh, etc.)
- System utilities and custom scripts
- Environment setup automation scripts
- Cross-platform compatibility (Linux/macOS)

## Technologies Used

- Bash/Shell scripting
- Vim configuration language
- Git configuration
- Tmux configuration
- Linux/Unix utilities
- Cross-platform shell scripting

## Installation

### Automatic Installation
```bash
# Clone the repository
git clone https://github.com/AR-92/dotfiles.git ~/.dotfiles
cd ~/.dotfiles

# Run the setup script (review it first!)
./setup.sh
```

### Manual Installation
To manually symlink specific configurations:
```bash
# Example for bashrc
ln -s ~/.dotfiles/.bashrc ~/.bashrc

# Example for vimrc
ln -s ~/.dotfiles/.vimrc ~/.vimrc
```

### Platform-Specific Setup
- **Linux**: Full compatibility with most distributions
- **macOS**: Includes macOS-specific configurations and workarounds

## Usage

These configuration files are meant to be used by symlinking them to your home directory or by copying them directly. The specific method depends on your workflow and preferences.

### Customization
- Modify the configuration files to suit your preferences
- Add platform-specific configurations in separate files
- Use the provided scripts to manage your environment

### Maintenance
- Regularly update the repository with your latest configurations
- Review and test changes before committing
- Keep sensitive information in separate, untracked files

## Project Structure

```
dotfiles/
├── .bashrc              # Bash configuration and aliases
├── .vimrc               # Vim editor configuration
├── .gitconfig           # Git configuration and aliases
├── .tmux.conf           # Tmux terminal multiplexer configuration
├── .ssh/config          # SSH configuration
├── bin/                 # Custom scripts and utilities
├── setup.sh             # Automated setup script
├── backup.sh            # Backup existing configurations
├── install.conf.yaml    # Dotbot configuration (if used)
├── macos/               # macOS-specific configurations
├── linux/               # Linux-specific configurations
├── themes/              # Color schemes and themes
└── README.md            # This file
```

## Configuration Files

### .bashrc
- Custom prompt with git branch detection
- Useful aliases and functions
- Path configurations
- Environment variables

### .vimrc
- Plugin configurations
- Key mappings
- Visual settings
- Custom functions

### .gitconfig
- User information
- Aliases for common git commands
- Diff and merge tools configuration
- Credential helpers

### .tmux.conf
- Key bindings
- Status bar customization
- Pane and window management
- Theme settings

## Contributing

While this is primarily a personal configuration repository, suggestions and improvements are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature-name`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some feature'`)
5. Push to the branch (`git push origin feature/your-feature-name`)
6. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

- GitHub: [AR-92](https://github.com/AR-92)