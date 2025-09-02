# dotfiles

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A collection of my configuration files for a consistent development environment across multiple systems.

## Description

This repository contains my personal configuration files (dotfiles) for various tools and applications I use in my development workflow. These configurations help me maintain a consistent and productive environment across different machines and operating systems.

## Key Features

- Terminal configuration (bashrc, aliases, etc.)
- Editor settings (vim, nano, etc.)
- Git configuration and aliases
- Development tool configurations
- System utilities and scripts
- Environment setup automation

## Technologies Used

- Bash
- Vim
- Git
- Linux/Unix utilities

## Installation

```bash
# Clone the repository
git clone https://github.com/AR-92/dotfiles.git ~/.dotfiles
cd ~/.dotfiles

# Symlink or copy configuration files to your home directory
# (The exact method depends on your preference and system setup)
```

## Usage

These configuration files are meant to be used by symlinking them to your home directory or by copying them directly. The specific method depends on your workflow and preferences.

Example of symlinking:
```bash
ln -s ~/.dotfiles/.bashrc ~/.bashrc
ln -s ~/.dotfiles/.vimrc ~/.vimrc
```

## Project Structure

```
dotfiles/
├── .bashrc              # Bash configuration
├── .vimrc               # Vim configuration
├── .gitconfig           # Git configuration
├── .aliases             # Shell aliases
├── scripts/             # Custom scripts
│   └── setup.sh         # Environment setup script
└── README.md
```

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