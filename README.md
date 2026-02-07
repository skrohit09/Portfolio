# GitHub Portfolio Website

A minimal and clean portfolio website that automatically syncs with your GitHub profile and displays all your repositories.

## Features

- 🔄 **Auto-sync**: Automatically fetches your GitHub profile and repositories
- 📊 **Statistics**: Shows your follower count, repository count, and following count
- 🎨 **Minimal Design**: Clean, elegant interface with smooth animations
- 📱 **Responsive**: Works perfectly on desktop, tablet, and mobile
- ⚡ **Fast**: Lightweight and optimized for performance

## Deployment to GitHub Pages

### Option 1: Quick Deploy (Recommended)

1. **Create a new repository**:
   - Go to [GitHub](https://github.com/new)
   - Name it: `skrohit09.github.io` (use your exact GitHub username)
   - Make it public
   - Don't initialize with README

2. **Upload the file**:
   - Click "uploading an existing file"
   - Drag and drop the `index.html` file
   - Commit the changes

3. **Enable GitHub Pages**:
   - Go to repository Settings → Pages
   - Source: Deploy from a branch
   - Branch: `main` and folder: `/ (root)`
   - Click Save

4. **Visit your site**:
   - Your website will be live at: `https://skrohit09.github.io`
   - It may take 1-2 minutes to deploy

### Option 2: Using Git (Command Line)

```bash
# Clone or create your repository
git clone https://github.com/skrohit09/skrohit09.github.io.git
cd skrohit09.github.io

# Copy the index.html file to this directory

# Add and commit
git add index.html
git commit -m "Initial portfolio website"

# Push to GitHub
git push origin main
```

Then enable GitHub Pages in your repository settings.

## Customization

The website automatically pulls data from your GitHub profile. To customize further:

- **Colors**: Edit the CSS variables in the `:root` section
- **Fonts**: Change the Google Fonts imports in the `<head>`
- **Layout**: Modify the HTML structure
- **Bio**: Your GitHub bio will automatically display (update it on GitHub)

## How It Works

The website uses the GitHub REST API to:
1. Fetch your profile information (name, bio, stats)
2. Retrieve all your public repositories
3. Display them sorted by last updated

No backend or API keys needed - it's completely static and free to host!

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## License

Feel free to use this template for your own portfolio!
