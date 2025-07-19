# Setup Instructions for Hong Kong ZK Workshop 2025

This document contains the setup instructions for the Hong Kong ZK Workshop. Please complete these steps before attending the workshop to ensure a smooth experience.

## General Requirements

- A laptop with a modern operating system (Windows, macOS, or Linux)
- Git
- A code editor (VS Code recommended)
- A terminal emulator
- At least 8GB RAM (16GB recommended for zkVM development)

## Prerequisites

### Install Node.js

Download and install Node.js (v18+) from [nodejs.org](https://nodejs.org/)

### Install Git

Download and install Git from [git-scm.com](https://git-scm.com/)

### Install a Code Editor

We recommend [Visual Studio Code](https://code.visualstudio.com/) with the following extensions:
- Rust (for zkVM development)
- Python (if needed for specific tools)
- GitLens (optional but helpful)

## Day 1: ZK Basics & Lattice ZKPs Setup

### Basic Development Environment

```bash
# Verify installations
node --version
git --version
```

### Optional: Install Python (if needed for specific tools)

```bash
# On macOS with Homebrew
brew install python

# On Ubuntu/Debian
sudo apt-get install python3 python3-pip

# On Windows, download from python.org
```

## Day 2: zkVM Development Setup

### Install Rust

```bash
# Install Rust using rustup
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

# Follow the prompts and restart your terminal
source ~/.bashrc  # or source ~/.zshrc for zsh
```

### Install Cargo (comes with Rust)

```bash
# Verify Rust and Cargo installation
rustc --version
cargo --version
```

### Install Common zkVM Tools

```bash
# Install common development tools
cargo install cargo-edit
cargo install cargo-watch
```

## Verify Your Installation

To verify that you have set up everything correctly, run the following commands:

```bash
node --version
git --version
rustc --version
cargo --version
```

All commands should return version numbers without errors.

## Workshop-Specific Tools

Additional tools and frameworks will be introduced during the workshop. The mentors will guide you through installing any specific tools needed for the hands-on sessions.

## Troubleshooting

### Common Issues

1. **Node.js not found**: Make sure Node.js is properly installed and added to your PATH
2. **Rust installation fails**: On Windows, you might need to install Visual Studio Build Tools
3. **Permission errors**: On Linux/macOS, you might need to use `sudo` for some installations

### Getting Help

If you encounter issues during setup:
1. Check the official documentation for each tool
2. Search for similar issues on Stack Overflow
3. Contact the workshop organizers at mo@ethereum.org

## Contact

For setup issues or questions:
- Email: mo@ethereum.org
- Event page: https://lu.ma/z4ikkbwj 