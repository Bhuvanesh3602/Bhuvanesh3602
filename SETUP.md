# GitHub Profile README Setup Guide

## 🚀 Quick Setup

### 1. Create Your Profile Repository
- Create a new repository with the same name as your GitHub username
- Make sure it's public
- Initialize with a README.md

### 2. Replace Placeholders
Replace the following placeholders in `README.md`:

- `[Your Name]` - Your actual name
- `[Your Current Project]` - Current project you're working on
- `[Technology you're learning]` - Technology you're currently learning
- `[your.email@example.com]` - Your email address
- `YourUsername` - Your GitHub username (appears multiple times)
- Social media links (LinkedIn, Twitter, Instagram, Portfolio)

### 3. Customize Tech Stack
Update the tech stack icons in the README by modifying the `skillicons.dev` URLs:
- Visit https://skillicons.dev/ to generate custom icon sets
- Replace the icon parameters with technologies you actually use

### 4. Enable Snake Animation
1. Copy the `.github/workflows/snake.yml` file to your profile repository
2. The workflow will automatically generate the snake animation
3. Make sure your repository has Actions enabled

### 5. Upload Custom Header (Optional)
1. Upload the `header.svg` to your repository
2. Replace the header image URL in README.md with:
   ```
   https://raw.githubusercontent.com/YourUsername/YourUsername/main/header.svg
   ```

## 🎨 Customization Options

### Themes
You can change the theme for all stats by replacing `tokyonight` with:
- `dark`
- `radical`
- `merko`
- `gruvbox`
- `onedark`
- `cobalt`
- `synthwave`
- `highcontrast`
- `dracula`

### Additional Widgets
Add more widgets by including these in your README:

#### WakaTime Stats (if you use WakaTime)
```markdown
[![wakatime](https://wakatime.com/badge/user/YourWakaTimeID.svg)](https://wakatime.com/@YourWakaTimeID)
```

#### Spotify Now Playing
```markdown
[![Spotify](https://novatorem.vercel.app/api/spotify)](https://open.spotify.com/user/YourSpotifyUsername)
```

#### Blog Posts (if you have a blog)
```markdown
### 📝 Latest Blog Posts
<!-- BLOG-POST-LIST:START -->
<!-- BLOG-POST-LIST:END -->
```

## 🔧 Advanced Features

### Auto-updating Blog Posts
1. Install the blog-post-workflow GitHub Action
2. Add RSS feed URL to the workflow
3. Blog posts will auto-update in your README

### Custom Metrics
Use GitHub Metrics action for more detailed statistics:
```yaml
- uses: lowlighter/metrics@latest
  with:
    token: ${{ secrets.METRICS_TOKEN }}
```

## 📱 Mobile Optimization
The README is designed to be mobile-friendly, but you can test it by:
1. Viewing your profile on mobile GitHub app
2. Adjusting image sizes if needed
3. Ensuring text remains readable

## 🎯 Tips for Best Results

1. **Keep it updated** - Regularly update your current projects and learning goals
2. **Be authentic** - Only include technologies you actually use
3. **Add personality** - Include fun facts and personal touches
4. **Optimize images** - Ensure all external images load quickly
5. **Test regularly** - Check that all links and images work properly

## 🚨 Troubleshooting

### Snake animation not showing?
- Check if GitHub Actions are enabled
- Verify the workflow file is in the correct location
- Ensure you have commits in your repository

### Stats not loading?
- Verify your username is correct in all URLs
- Check if the external services (Vercel apps) are working
- Try refreshing after a few minutes

### Images not displaying?
- Ensure image URLs are accessible
- Check if external services are online
- Verify file paths for custom images

## 🌟 Inspiration
Check out these amazing GitHub profiles for inspiration:
- [abhisheknaiidu/awesome-github-profile-readme](https://github.com/abhisheknaiidu/awesome-github-profile-readme)
- [kautukkundan/Awesome-Profile-README-templates](https://github.com/kautukkundan/Awesome-Profile-README-templates)

Happy coding! 🚀