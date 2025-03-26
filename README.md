# MacDown Themes Collection

A collection of custom themes and styles for the MacDown markdown editor, focusing on modern design principles and readability.

## Repository Structure

This repository contains both editor styles (CSS) and syntax highlighting themes:

```
.
├── README.md
├── styles/           # CSS styles for markdown preview
│   └── *.css
├── themes/           # Syntax highlighting themes
│   └── *.style
└── .gitignore
```

## Installation

### Option 1: Symlinks (Recommended)

This method keeps your themes in sync with the repository:

```bash
# Create symlinks (after backing up existing folders if needed)
ln -sf ~/Projects/macdown-themes/styles/* ~/Library/Application\ Support/MacDown/Styles/
ln -sf ~/Projects/macdown-themes/themes/* ~/Library/Application\ Support/MacDown/Themes/
```

### Option 2: Manual Copy

1. Clone this repository:
   ```bash
   git clone [repository-url]
   ```

2. Copy the desired files:
   ```bash
   # For CSS preview styles
   cp styles/*.css ~/Library/Application\ Support/MacDown/Styles/
   
   # For syntax highlighting themes
   cp themes/*.style ~/Library/Application\ Support/MacDown/Themes/
   ```

3. In MacDown's preferences:
   - Go to the "Editor" tab
   - Select your installed theme from the "Theme" dropdown
   - Select your installed style from the "Style" dropdown

## Available Styles

### Mou Night+ Modern v1
A modern take on the classic Mou Night+ theme, featuring:
- Radix UI inspired design elements
- Variable-based color system
- Modern spacing and typography
- Enhanced table styles
- Improved code blocks
- Print-friendly styles

[List continues with other styles...]

## Available Themes

- Mou Fresh Air/Air+
- Mou Night/Night+
- Mou Paper/Paper+
- Solarized (Dark/Light)
- Tomorrow/Tomorrow+
- Writer/Writer+

## Theme Development

### CSS Variables

The styles use CSS variables for easy customization. Common variables include:

```css
--bg-primary: Main background color
--text-primary: Primary text color
--heading-color: Heading text color
--link-color: Link color
--code-color: Code text color
```

See individual style files for complete variable lists.

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

MIT License
