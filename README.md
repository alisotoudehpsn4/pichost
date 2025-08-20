# PicHost - Simple Image Hosting

A simple, client-side image hosting website that can be deployed on GitHub Pages.

## Features

- **Drag & Drop Upload**: Simply drag images into the upload area
- **Multiple File Support**: Upload multiple images at once
- **Image Preview**: View uploaded images in a responsive gallery
- **Copy Links**: One-click copying of image URLs
- **Local Storage**: Images are stored locally in your browser
- **Responsive Design**: Works on desktop and mobile devices
- **No Server Required**: Pure client-side application

## Deployment on GitHub Pages

1. **Create a new repository** on GitHub (or use an existing one)

2. **Upload the files**:
   - Upload `index.html` to the root of your repository
   - Commit the changes

3. **Enable GitHub Pages**:
   - Go to your repository settings
   - Scroll down to "Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)"
   - Click Save

4. **Access your site**:
   - Your site will be available at: `https://yourusername.github.io/yourrepository`
   - It may take a few minutes for the site to become available

## How It Works

This is a client-side only application that uses:
- **Local Storage** to save image data in your browser
- **File API** to handle image uploads
- **Base64 encoding** to store images as data URLs

**Note**: Images are stored locally in your browser and will persist across sessions. However, they won't be accessible from other devices or browsers.

## Customization

You can easily customize the appearance by modifying the CSS in `index.html`:
- Change colors by updating the CSS variables
- Modify the gradient background
- Adjust the layout and spacing
- Update the branding and text

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge

## Limitations

- Images are stored in browser's localStorage (5-10MB limit typically)
- Images are not actually hosted on a server - they exist only in your browser
- For true image hosting, you'd need to integrate with a backend service

## License

Free to use and modify for any purpose.