# Hosting the PDF Compressor on GitHub Pages

This document provides step-by-step instructions on how to host the PDF Compressor web application on GitHub Pages for free.

## Prerequisites

1. A GitHub account
2. Basic knowledge of GitHub (creating repositories, committing files)

## Step 1: Create a New GitHub Repository

1. Log in to your GitHub account
2. Click on the "+" icon in the top right and select "New repository"
3. Name your repository (e.g., "pdf-compressor")
4. Optionally add a description
5. Choose "Public" visibility (GitHub Pages requires a public repository, unless you have GitHub Pro)
6. Click "Create repository"

## Step 2: Upload the Files

### Option 1: Using GitHub Web Interface

1. In your new repository, click on "Add file" and select "Upload files"
2. Drag and drop all the files and folders from this project
3. Add a commit message like "Initial commit"
4. Click "Commit changes"

### Option 2: Using Git Command Line

1. Clone the repository to your local machine:
   ```
   git clone https://github.com/YOUR_USERNAME/pdf-compressor.git
   ```
2. Copy all files from this project into the cloned directory
3. Add all files, commit and push:
   ```
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

## Step 3: Configure GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings"
3. Scroll down to the "GitHub Pages" section (or click on "Pages" in the left sidebar)
4. Under "Source", select "main" or "master" branch
5. Click "Save"
6. Wait a few minutes for GitHub to build and deploy your site

## Step 4: Access Your Website

After GitHub Pages builds your site, you'll see a message like:
> Your site is published at https://YOUR_USERNAME.github.io/pdf-compressor/

Click on the link to visit your hosted PDF Compressor application.

## Customizing Your Site

Feel free to customize:
- The title and description in index.html
- Colors and styles in css/custom.css
- Add your name/copyright in the footer

## Troubleshooting

If your site doesn't appear:
1. Make sure your repository is public
2. Check that the file structure is correct (index.html should be at the root)
3. Wait a few minutes for GitHub to build your site
4. Check the "Actions" tab for any build errors

## Limitations of GitHub Pages

Remember that GitHub Pages only hosts static websites. This means:
1. No server-side processing
2. All PDF compression happens in the client's browser
3. Very large PDFs might cause browser performance issues

For a more robust solution with server-side processing, consider hosting the original Flask application on a server that supports Python.