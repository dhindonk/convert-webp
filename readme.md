# PNG/JPG to WebP Converter - Privacy First 🔒

A client-side, privacy-focused tool for converting PNG and JPG images to WebP format directly in your browser. No server uploads, no data collection, just pure browser-based conversion.

## ✨ Features

### 🔒 Privacy Features
- **100% Client-Side Processing**: All image conversions happen directly in your browser
- **No Server Uploads**: Your images never leave your device
- **No Data Collection**: We don't track, store, or collect any usage data
- **Local Storage Only**: Converted images are temporarily stored in your browser's local storage

### 💡 Key Features
- Convert PNG/JPG images to WebP format
- Adjustable WebP quality settings (0.1 to 1.0)
- Batch conversion support
- Drag & drop interface
- Download individual WebP files
- Bulk download as ZIP
- File size comparison
- Maximum file size: 10MB per image
- Automatic progress tracking

## 🚀 Usage

1. Open the converter in your web browser
2. Drag & drop images or click to select files
3. Adjust the WebP quality if needed (default: 0.95)
4. Click "Convert to WebP"
5. Download individual files or all as ZIP

## 💻 Technical Details

- Built with pure JavaScript - no external dependencies except JSZip
- Uses modern browser APIs:
  - Canvas API for image processing
  - File API for handling uploads
  - Blob API for file downloads
  - Local Storage for temporary data persistence
  - Web Workers for efficient processing

## 🛠️ Development

To run this project locally:

1. Clone the repository
```bash
git clone https://github.com/dhindonk/convert-webp.git
```

2. Open index.html in your browser

No build process or dependencies needed!

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 👨‍💻 Author

Made with ❤️ by **Moch. Fahdin**

- LinkedIn: [Moch. Fahdin](https://www.linkedin.com/in/moch-fahdin-453b0a286/)
- GitHub: [@dhindonk](https://github.com/dhindonk/)

## 📝 License

This project is open source and available under the [MIT License](LICENSE).
