# Awesome Bashrc 🐚✨

![Awesome Bashrc](https://img.shields.io/badge/Download%20Latest%20Release-Click%20Here-brightgreen)

Welcome to **Awesome Bashrc**, an optimized `.bashrc` template designed specifically for High-Performance Computing (HPC) users. This repository offers a streamlined approach to managing your command line environment, making your work more efficient and enjoyable. Whether you are using TACC's Lonestar 6 or UCAR's HPC systems, this template will enhance your productivity.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)
- [Support](#support)

## Features 🌟

The **Awesome Bashrc** template comes packed with features tailored for HPC users:

- **Module Management**: Easily load and unload software modules.
- **Auto-Backup**: Automatically back up your configuration files.
- **Custom Aliases**: Simplify common commands with user-defined aliases.
- **Environment Redirection**: Manage environment variables effectively.
- **Cross-Compatibility**: Works seamlessly on various HPC systems.

## Installation 🛠️

To get started with **Awesome Bashrc**, follow these simple steps:

1. **Download the Latest Release**: Visit the [Releases section](https://github.com/Space-Rider942/awesome-bashrc/releases) to download the latest version of the `.bashrc` template. Make sure to download the file and execute it.

2. **Copy to Home Directory**: Once downloaded, copy the `.bashrc` file to your home directory:

   ```bash
   cp path/to/downloaded/.bashrc ~/
   ```

3. **Source the File**: To apply the changes, run the following command:

   ```bash
   source ~/.bashrc
   ```

Now you are all set to use your new optimized `.bashrc`!

## Usage 📚

The **Awesome Bashrc** template enhances your command line experience. Here are some key commands and features:

### Module Management

Use the following commands to manage your software modules:

- **Load a Module**: 
  ```bash
  module load <module_name>
  ```

- **Unload a Module**: 
  ```bash
  module unload <module_name>
  ```

- **List Loaded Modules**: 
  ```bash
  module list
  ```

### Custom Aliases

The template includes several predefined aliases to speed up your workflow. Here are a few examples:

- **List Files**: 
  ```bash
  alias ll='ls -la'
  ```

- **Navigate Up a Directory**: 
  ```bash
  alias ..='cd ..'
  ```

Feel free to customize these aliases to fit your needs.

### Auto-Backup

The auto-backup feature automatically saves a copy of your `.bashrc` file every time you make changes. You can find the backups in the `~/.bashrc_backups` directory.

### Environment Redirection

You can set environment variables easily with the following syntax:

```bash
export VARIABLE_NAME=value
```

## Configuration ⚙️

The **Awesome Bashrc** template is highly configurable. You can modify various settings to suit your preferences:

1. **Edit Aliases**: Open the `.bashrc` file and scroll to the aliases section to add or change commands.

2. **Change Backup Settings**: Adjust the backup frequency or location by modifying the corresponding variables in the `.bashrc`.

3. **Module Settings**: If you use specific modules frequently, you can pre-load them in the `.bashrc` file.

## Contributing 🤝

We welcome contributions from the community! If you would like to improve this project, please follow these steps:

1. **Fork the Repository**: Click on the "Fork" button at the top right of the page.

2. **Create a New Branch**: 
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make Your Changes**: Edit the files as needed.

4. **Commit Your Changes**: 
   ```bash
   git commit -m "Add your message here"
   ```

5. **Push to Your Fork**: 
   ```bash
   git push origin feature/your-feature-name
   ```

6. **Open a Pull Request**: Go to the original repository and click on "New Pull Request."

## License 📄

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Support 💬

If you encounter any issues or have questions, feel free to open an issue in the repository. You can also check the [Releases section](https://github.com/Space-Rider942/awesome-bashrc/releases) for updates and downloads.

Thank you for using **Awesome Bashrc**! We hope it enhances your HPC experience.