# PDF Compressor

A web application that compresses PDF files from ~80MB to ~4MB while maintaining document quality.

## Features

- Drag and drop interface for easy file uploads
- Client-side processing (files never leave your browser)
- Maintains document quality while reducing file size
- Displays compression statistics (size reduction, compression ratio)
- Fully responsive design
- Works offline once loaded

## Usage

1. Drag and drop a PDF file or click to select a file
2. Click the "Compress" button to start compression
3. When compression is complete, click "Download" to save the compressed file

## Technical Details

This application uses several libraries to handle PDF compression:

- PDF.js for parsing PDF documents
- pdf-lib.js for PDF manipulation
- Bootstrap for UI components

All processing happens in the browser - no server-side processing is involved.

## Limitations

Browser-based PDF compression has limitations compared to server-side solutions:

- Limited compression capabilities for very large files
- Might work slower on low-end devices 
- Some complex PDF features may not compress optimally

## Deploying to GitHub Pages

This is a static website that can be hosted on GitHub Pages. To deploy:

1. Fork this repository
2. Go to the repository settings on GitHub
3. Navigate to "Pages" under "Code and automation"
4. Select your main branch as the source
5. Click "Save"

Your site will be published at `https://[your-username].github.io/[repository-name]/`