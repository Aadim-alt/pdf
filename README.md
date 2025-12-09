# 📄 PDF Converter Tool

![PDF Converter](https://img.shields.io/badge/status-active-success.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

A powerful, client-side web tool for converting images and ODT files to PDF format. No server required - all processing happens directly in your browser!

🔗 **Live Demo:** [https://aadim-alt.github.io/pdf/](https://aadim-alt.github.io/pdf/)

## ✨ Features

### Three Conversion Modes
- **📷 Single Image to PDF** - Convert one image at a time
- **🖼️ Multiple Images to PDF** - Combine multiple images into a single PDF document
- **📝 ODT to PDF** - Convert OpenDocument Text files to PDF format

### User-Friendly Interface
- 📤 Drag-and-drop file upload
- 👁️ Real-time image preview
- 📊 Progress bar during conversion
- ✅ Success/error notifications
- 📱 Fully responsive design (works on desktop and mobile)
- 🎨 Beautiful gradient UI with smooth animations

### Technical Features
- ✅ Supports multiple image formats: JPG, PNG, BMP, GIF, WebP
- ✅ Handles ODT (OpenDocument Text) files
- ✅ Maximum file size: 10MB per file
- ✅ Automatic image sizing to fit PDF pages
- ✅ Multi-page PDF generation
- ✅ 100% client-side processing (no data leaves your browser)
- ✅ No backend server required

## 🚀 Quick Start

### Using the Tool

1. **Visit the website:** [https://aadim-alt.github.io/pdf/](https://aadim-alt.github.io/pdf/)
2. **Select conversion type:**
   - Click on "Single Image", "Multiple Images", or "ODT to PDF"
3. **Upload your files:**
   - Drag and drop files into the upload area, OR
   - Click the upload area to browse and select files
4. **Convert:**
   - Click the "Convert to PDF" button
5. **Download:**
   - Your PDF will be automatically generated and downloaded

## 📖 Detailed Usage Instructions

### Single Image to PDF
1. Select "Single Image" mode
2. Upload one image file (JPG, PNG, BMP, GIF, WebP)
3. The image will be centered and fitted to the PDF page
4. Click "Convert to PDF" to download

### Multiple Images to PDF
1. Select "Multiple Images" mode
2. Upload multiple image files
3. Each image will be placed on a separate page
4. Images are automatically resized to fit each page
5. Click "Convert to PDF" to create a multi-page PDF

### ODT to PDF
1. Select "ODT to PDF" mode
2. Upload an OpenDocument Text (.odt) file
3. The text content will be extracted and formatted
4. Click "Convert to PDF" to download the converted document

## 🛠️ Technologies Used

- **HTML5** - Structure and markup
- **CSS3** - Styling with gradients and animations
- **JavaScript (ES6+)** - Core functionality
- **[jsPDF](https://github.com/parallax/jsPDF)** - PDF generation library
- **[Mammoth.js](https://github.com/mwilliamson/mammoth.js)** - ODT text extraction

## 📦 Installation for Local Development

1. **Clone the repository:**
   ```bash
   git clone https://github.com/aadim-alt/pdf.git
   cd pdf
   ```

2. **Open in browser:**
   - Simply open `index.html` in your web browser
   - No build process or dependencies to install!

3. **Or use a local server (optional):**
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js with npx
   npx http-server
   ```
   Then visit `http://localhost:8000`

## 🌐 Deployment to GitHub Pages

This project is already deployed! But if you want to deploy your own version:

1. Fork this repository
2. Go to **Settings** → **Pages**
3. Under "Source", select **Deploy from a branch**
4. Choose **main** branch and **/ (root)** folder
5. Click **Save**
6. Your site will be live at `https://yourusername.github.io/pdf/`

## 📝 File Structure

```
pdf/
├── index.html          # Main application file (contains HTML, CSS, JS)
└── README.md           # This file
```

## 🔒 Privacy & Security

- ✅ **100% Client-Side Processing** - All conversions happen in your browser
- ✅ **No Data Upload** - Your files never leave your device
- ✅ **No Server** - No backend means no data storage
- ✅ **Secure** - Works offline once loaded

## 🐛 Known Limitations

- Maximum file size: 10MB per file
- ODT conversion extracts plain text only (formatting may be limited)
- Complex ODT documents with images/tables may not convert perfectly
- Large images may take a few seconds to process

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some amazing feature'`)
5. Push to the branch (`git push origin feature/amazing-feature`)
6. Open a Pull Request

### Ideas for Contributions
- Add support for more file formats (DOCX, TXT, etc.)
- Implement PDF compression
- Add watermark feature
- Custom page sizes and orientations
- Batch download as ZIP
- PDF password protection

## 📜 License

This project is licensed under the MIT License - see below for details:

```
MIT License

Copyright (c) 2025 aadim-alt

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 👤 Author

**aadim-alt**
- GitHub: [@aadim-alt](https://github.com/aadim-alt)
- Project: [https://github.com/aadim-alt/pdf](https://github.com/aadim-alt/pdf)

## 🌟 Show Your Support

Give a ⭐️ if this project helped you!

## 📞 Support

If you have any questions or run into issues:
1. Check the [Issues](https://github.com/aadim-alt/pdf/issues) page
2. Open a new issue if your problem isn't already listed
3. Provide as much detail as possible (browser, file type, error message)

## 🔄 Version History

### v1.0.0 (Current)
- Initial release
- Single image to PDF conversion
- Multiple images to PDF conversion
- ODT to PDF conversion
- Drag-and-drop upload
- Responsive design

---

Made with ❤️ by [aadim-alt](https://github.com/aadim-alt)
