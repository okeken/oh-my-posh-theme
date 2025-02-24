# Oh My Posh Theme Configuration

This repository contains a custom Oh My Posh theme configuration file designed to enhance your terminal prompt with a visually appealing and functional layout. The configuration includes segments for displaying the current directory, Git status, battery level, time, and more.

## Features

- **Path Segment**: Displays the current directory path with a folder icon and custom styling.
- **Git Segment**: Shows the current Git branch with a lightning bolt icon.
- **Root Indicator**: Displays a `root` indicator when running as a superuser.
- **Dart/Flutter Segment**: Displays the current Dart or Flutter version.
- **Node.js Segment**: Shows the current Node.js version with an icon.
- **Python Segment**: Displays the active Python virtual environment.
- **Battery Segment**: Shows the battery status (charging, discharging, or full) with dynamic colors.
- **Time Segment**: Displays the current date and time.

## Configuration Overview

The configuration is structured into three main blocks:

1. **Left-Aligned Block**:
   - **Path Segment**: Displays the current directory.
   - **Git Segment**: Displays the current Git branch.
   - **Text Segment**: Adds a decorative diamond icon.

2. **Newline Block**:
   - **Text Segment**: Adds a simple `>` symbol on a new line.

3. **Right-Aligned Block**:
   - **Root Indicator**: Displays `root` when applicable.
   - **Dart/Flutter Segment**: Shows the Dart/Flutter version.
   - **Node.js Segment**: Shows the Node.js version.
   - **Python Segment**: Displays the active Python virtual environment.
   - **Battery Segment**: Shows the battery status.
   - **Time Segment**: Displays the current date and time.

## Installation and Usage

1. **Install Oh My Posh**:
   Follow the official [Oh My Posh installation guide](https://ohmyposh.dev/docs/installation) to set up Oh My Posh on your system.

2. **Apply the Theme**:
   Use the following command to apply the theme directly from the provided URL:

   ```bash
   oh-my-posh init <shell> --config 'https://raw.githubusercontent.com/okeken/oh-my-posh-theme/main/schema.json'
   ```
   Replace <shell> with your shell type (e.g., bash, zsh, fish, etc.).
   
3. **Reload Your Shell**:
   After applying the theme, reload your shell configuration to see the changes:
   
   ```bash
   source ~/.bashrc  # or ~/.zshrc, depending on your shell
   ```
4. **Theme Path and Schema:**:
   Theme Path and Schema:

   ```bash
   https://raw.githubusercontent.com/okeken/oh-my-posh-theme/main/schema.json
   ```
   The JSON schema for this theme is available at:
   
   ```bash
   https://github.com/okeken/oh-my-posh-theme/blob/main/schema.json
   ```
   Refer to the schema for detailed information about the structure and customization options.

## Customization
You can customize the theme by editing the JSON configuration file. Refer to the Oh My Posh documentation for details on available segments, properties, and styling options.

Example
Here’s how the prompt might look with this configuration:

```bash
~/projects/my-repo  ⚡ main  ♦
> 
| root | 🎯 Dart 2.15.0 | 🟢 Node 16.13.0 | 🐍 venv | ⚡ 85% ████████▌ | 2023-10-05 14:30
```

## License
This configuration is provided under the MIT License. Feel free to use, modify, and distribute it as needed.

Enjoy your enhanced terminal experience! 🚀

## Heaviy Inspired by
 - https://github.dev/JanDeDobbeleer/oh-my-posh/blob/main/themes/negligible.omp.json
 - https://github.com/JanDeDobbeleer/oh-my-posh/blob/main/themes/json.omp.json
