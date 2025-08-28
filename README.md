# VIRTUALIZATION-CONVERT-IMAGE-FILE-FORMATS 💿→📀

![GitHub stars](https://img.shields.io/github/stars/LINUX-OASIS/VIRTUALIZATION-CONVERT-IMAGE-FILE-FORMATS?style=social)
![GitHub forks](https://img.shields.io/github/forks/LINUX-OASIS/VIRTUALIZATION-CONVERT-IMAGE-FILE-FORMATS?style=social)
![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)
![GitHub issues](https://img.shields.io/github/issues/LINUX-OASIS/VIRTUALIZATION-CONVERT-IMAGE-FILE-FORMATS)
![GitHub pull requests](https://img.shields.io/github/issues-pr/LINUX-OASIS/VIRTUALIZATION-CONVERT-IMAGE-FILE-FORMATS)
![Shell Script](https://img.shields.io/badge/shell_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)

A user-friendly Bash script with a `whiptail` TUI to effortlessly convert virtual machine disk images between various formats.

---

## ✨ Features

*   **Interactive TUI**: Simple and intuitive terminal-based UI powered by `whiptail`.
*   **Automatic Discovery**: Scans the current directory for compatible image files and presents them in a menu.
*   **Manual File Selection**: Option to provide a direct path to an image file anywhere on your system.
*   **Dependency Check**: Automatically verifies if `qemu-img` is installed and provides installation instructions if it's missing.
*   **Wide Format Support**: Convert between all major virtual disk formats.
*   **Safety First**: Includes a double-confirmation prompt before starting the conversion process to prevent accidental changes.

## ⚙️ Supported Formats

This script leverages the power of `qemu-img` to convert between the following formats:

*   `.vdi` (VirtualBox Disk Image)
*   `.vhd` (Virtual Hard Disk)
*   `.vmdk` (VMware Virtual Machine Disk)
*   `.qcow` / `.qcow2` (QEMU Copy On Write)
*   `.qed` (QEMU Enhanced Disk Format)
*   `.img` / `.bin` (Raw Disk Image)

## 🖥️ Compatibility

This script is designed for Linux and is compatible with most modern distributions.

✅ **Confirmed working on:**
*   Debian
*   Ubuntu
*   Linux Mint
*   Other Debian/APT-based distributions

It should also work flawlessly on other systems like **Fedora** or **Arch Linux**, provided the dependencies are met.

## 🧩 Dependencies

The script relies on a couple of key components:

*   **`qemu-utils`**: This package provides the core `qemu-img` conversion utility. The script will automatically check if `qemu-img` is available. If not, it will display instructions for installing it on Debian, Fedora, and Arch-based systems.
*   **`whiptail`**: This utility is used to create the dialog boxes for the TUI. It is typically pre-installed on most desktop Linux distributions (as part of the `newt` or `libnewt` package).

## 🚀 Getting Started

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/LINUX-OASIS/VIRTUALIZATION-CONVERT-IMAGE-FILE-FORMATS.git
    cd VIRTUALIZATION-CONVERT-IMAGE-FILE-FORMATS
    ```

2.  **Make the script executable:**
    ```bash
    chmod +x custom-VIRTUALIZATION-CONVERT-IMAGE-FILE-FORMATS.sh
    ```

3.  **Run the script:**
    ```bash
    ./custom-VIRTUALIZATION-CONVERT-IMAGE-FILE-FORMATS.sh
    ```

4.  Follow the on-screen prompts to select your image file and target format!

## 💬 Contributing

[Pull requests](https://github.com/LINUX-OASIS/VIRTUALIZATION-CONVERT-IMAGE-FILE-FORMATS/pulls), [issues](https://github.com/LINUX-OASIS/VIRTUALIZATION-CONVERT-IMAGE-FILE-FORMATS/issues), and suggestions are warmly welcomed!

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## 🌐 Links

*   [Issues](https://github.com/LINUX-OASIS/VIRTUALIZATION-CONVERT-IMAGE-FILE-FORMATS/issues)
*   [Pull Requests](https://github.com/LINUX-OASIS/VIRTUALIZATION-CONVERT-IMAGE-FILE-FORMATS/pulls)
*   [Releases](https://github.com/LINUX-OASIS/VIRTUALIZATION-CONVERT-IMAGE-FILE-FORMATS/releases)
*   [Wiki](https://github.com/LINUX-OASIS/VIRTUALIZATION-CONVERT-IMAGE-FILE-FORMATS/wiki)

## 🧙‍♂️ Maintainer

*   **[LINUX-OASIS](https://github.com/LINUX-OASIS)**

## 📜 License

This project is licensed under the **GNU General Public License v3.0**. See the `LICENSE` file for details.
