# elo2025-paradox

Academic presentation slides built with reveal.js.

## Quick Start

### View locally:
```bash
# Using Python (recommended)
python3 -m http.server 8000

# Or using Node.js
npm run serve
```

Then open http://localhost:8000 in your browser.

### GitHub Pages

1. Go to Settings → Pages
2. Set source to "Deploy from a branch"
3. Select "main" branch and "/ (root)" folder
4. Your slides will be available at: `https://[username].github.io/elo2025-paradox/`

## Editing Slides

Edit `slides.md` using Markdown. The presentation supports:

- Horizontal slides: Separate with `---`
- Vertical slides: Separate with `--`
- Speaker notes: Add after `Note:`
- Math equations: Use `$...$` for inline, `$$...$$` for blocks
- Code highlighting: Use fenced code blocks
- Fragments: Add `<!-- .element: class="fragment" -->`

## Keyboard Shortcuts

- **Arrow keys**: Navigate slides
- **F**: Fullscreen
- **S**: Speaker notes
- **O**: Overview mode
- **ESC**: Exit fullscreen/overview
- **Alt + Click**: Zoom in
- **Ctrl + F**: Search

## Mobile Editing

### Method 1: GitHub Mobile App
1. Install GitHub mobile app
2. Navigate to your repository
3. Edit `slides.md` directly
4. To add images:
   - Tap "+" → "Upload files"
   - Select images from your phone
   - Upload to the `images/` folder
   - Reference in slides: `![Description](images/your-image.jpg)`

### Method 2: GitHub.dev
1. Open in mobile browser: `github.dev/[username]/elo2025-paradox`
2. Edit files with VS Code interface
3. Drag and drop or paste images directly

### Adding Images to Slides
```markdown
![Image description](images/photo.jpg)

<!-- With custom size -->
![Image description](images/photo.jpg) <!-- .element: style="width: 50%;" -->

<!-- Centered -->
![Image description](images/photo.jpg) <!-- .element: class="r-stretch" -->
```

## Themes

Change the theme in `index.html` by modifying the theme CSS link:
- `white` (default)
- `black`
- `league`
- `beige`
- `sky`
- `night`
- `serif`
- `simple`
- `solarized`