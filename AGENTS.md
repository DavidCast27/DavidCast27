# AGENTS.md - GitHub Profile Maintenance Guidelines

## Repository Purpose
This repository exists solely to customize David Castrillón's GitHub profile page. When a GitHub repository matches a username exactly (DavidCast27), its README.md is automatically displayed on the user's profile page at https://github.com/DavidCast27.

## Repository Structure
- `README.md` - The content shown on the GitHub profile page
- `assets/` - Static assets (SVG icons) referenced in the README

## Profile Content Guidelines

### README.md Best Practices
- Use GitHub Flavored Markdown (GFM) with limited HTML support
- Keep content scannable and visually balanced
- Use `<div align="center">` for centering content blocks
- Separate sections with horizontal rules (`<hr/>`)
- Optimize all images (recommended icon size: 30-50px width)
- Use absolute URLs for external links (to profiles, projects, etc.)
- Include descriptive alt text for meaningful images
- Add title attributes to image links for tooltip information on hover
- Maintain consistent spacing with `<br/>` and `<p>` tags

### Asset Management
- Store all SVG icons in the assets/ directory
- Prefer SVG format for scalability and small file size
- Optimize SVGs by removing unnecessary metadata
- Use descriptive, lowercase filenames with hyphens (e.g., react.svg)
- Maintain consistent icon sizes throughout the README (typically 30-50px)
- Source icons from reputable providers like simpleicons.org
- Commit asset files together with README changes that reference them

### Recommended Content Structure
1. **Header Section**: Personal greeting and role identification
2. **About Me**: Brief professional/personal description (2-3 sentences max)
3. **Skills/Tools Grid**: Visual showcase using SVG icons (grouped by category)
4. **Connect Section**: Links to professional profiles (LinkedIn, Twitter, etc.)
5. **Footer**: Credits to icon sources or acknowledgments

### Technical Constraints to Remember
- GitHub profile READMEs support only basic HTML tags (no custom CSS/JS)
- All images must be hosted in the repository (use relative paths like `assets/icon.svg`)
- External image hosting is discouraged and may not work reliably
- Animated GIFs function but should be used minimally to avoid distraction
- Maximum repository size limits apply (keep assets lightweight)
- GitHub treats file paths as case-sensitive

## Profile Update Procedures

### Modifying Text Content
1. Edit README.md directly in the repository
2. Changes appear on your profile within seconds
3. Use GitHub's markdown preview or local markdown viewer to verify formatting
4. Always test hyperlinks before committing
5. Keep paragraphs concise for mobile viewing

### Adding/Updating Skills Icons
1. Place new SVG files in the assets/ directory
2. Reference them in README.md using: `<img src="assets/filename.svg" width="X">`
3. Commit both the asset file and README changes in the same commit
4. Remove unused assets periodically to keep repository lean
5. Verify icon paths are correct and case-sensitive

### Common Maintenance Tasks
- **Update bio**: Modify the "About me" section in README.md
- **Add new technology**: Place icon in assets/, update relevant skills section
- **Change profile link**: Update URL in "Connect with me" section
- **Refresh credits**: Acknowledge new icon sources or tools as needed
- **Fix broken images**: Verify file paths and capitalization in assets/

## Design Principles for Profile READMEs

### Visual Hierarchy
- Use header sizes strategically (h1 for name, h2 for sections, h3 for subsections)
- Place most important information near the top (above the fold)
- Create visual breathing room with `<br/>` and `<p>` elements
- Maintain consistent alignment (prefer center-aligned for profile content)
- Use emojis sparingly as visual markers (not as primary content)

### Accessibility Considerations
- Ensure sufficient contrast between emojis/icons and background
- Provide contextual meaning for icons (don't rely solely on imagery)
- Avoid using color alone to convey information
- Use semantic HTML elements where supported (<strong>, <em>, etc.)
- Keep language clear and concise for screen readers

### Performance Optimization
- Minimize asset file sizes (aim for SVGs under 10KB when possible)
- Limit total number of images to prevent slow loading
- Consider that profile views may occur on slower connections
- Test how your profile appears when images fail to load
- Remember that GitHub profiles are viewed frequently and should load instantly

## Maintenance Workflow

### Making Changes
1. Navigate to this repository on GitHub or locally
2. Edit README.md directly using GitHub's web editor or preferred IDE
3. For asset changes: add/update files in assets/ directory
4. Preview changes using GitHub's markdown rendering
5. Commit with a descriptive message explaining the update
6. Changes appear on your profile immediately after commit

### Commit Message Examples
- `update: add python icon to skills section`
- `fix: correct linkedin url in connect section`
- `docs: refresh about me with current professional focus`
- `assets: optimize svg files for faster loading`
- `style: adjust spacing in tools section for better mobile view`
- `chore: remove unused icon assets`

## Troubleshooting Common Issues

### Images Not Displaying
- Verify file path exactly matches case (GitHub is case-sensitive)
- Confirm file exists in assets/ directory
- Check for typos in filename or extension
- Ensure you committed the asset file along with README changes

### Formatting Problems
- Validate markdown syntax using a markdown previewer
- Check that HTML tags are properly closed
- Verify alignment attributes are correctly formatted
- Ensure horizontal rules (`<hr/>`) are on their own lines

### Links Not Working
- Test all URLs before committing
- Use absolute URLs including https:// prefix
- Verify LinkedIn and other profile links are current
- Check for trailing slashes or extra spaces in URLs

### Layout Issues on Mobile
- Keep lines of text reasonably short for mobile viewing
- Test how centered content appears on narrow screens
- Avoid overly wide tables or preformatted blocks
- Consider that some users will view your profile on smartphones

## Important Limitations to Remember
- This repository is **not** for hosting applications or code projects
- No build process, linting, or testing is applicable or needed
- The sole purpose is visual presentation of your GitHub profile
- Content appears exactly as rendered in README.md - no processing occurs
- Updates are instantaneous - no waiting for builds or deployments
- The primary value is in creating a professional, engaging profile snapshot

## Last Updated: March 21, 2026
*These guidelines help maintain a consistent, professional GitHub profile that accurately represents David Castrillón's skills and professional presence.*
