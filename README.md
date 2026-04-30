# Fastfetch Setup

This repository contains my personal Fastfetch configuration files and related assets for customizing the system information display.

## What is Fastfetch?

Fastfetch is a tool that displays system information in a neat and customizable way. It's similar to Neofetch but faster and more feature-rich.

## Installation

To use Fastfetch, you need to install it first. On Fedora, you can install it via:

```bash
sudo dnf install fastfetch
```

For other distributions, check the [official repository](https://github.com/fastfetch-cli/fastfetch) for installation instructions.

## Starter Setup

If you want to use this repo as a starter configuration, first `cd ~/.config` and then clone the repo:

```bash
cd ~/.config
git clone https://github.com/Anoteros/fastfetch
```

## Usage

To run Fastfetch with the provided configuration:

```bash
fastfetch
```

## Fonts

This configuration uses Nerd Font icons, so you should install a patched font such as **FiraCode Nerd Font** for the icons to display correctly. You can download it from:

- https://www.nerdfonts.com/
- https://github.com/ryanoasis/nerd-fonts

After installing the font, make sure your terminal is configured to use the patched Nerd Font.

## Repository Structure

- `configs/`: Contains Fastfetch configuration JSON files.
- `logos/`: Directory for custom logos.
  - `txt/`: Text-based logos (ASCII art).
  - `image/`: Image-based logos (PNG, JPG, etc.).
- `LICENSE`: The license for this repository.
- `README.md`: This file.

## Customization

The configuration in `configs/config.json` includes modules for displaying various system information like OS, kernel, packages, shell, etc. You can modify the JSON to add, remove, or customize modules according to your needs.

For more information on configuration options, refer to the [Fastfetch documentation](https://github.com/fastfetch-cli/fastfetch/wiki).

## Contributing

This is a personal repository, but feel free to fork and adapt it for your own use.

## License

See [LICENSE](LICENSE) for details.