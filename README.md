# MacDown Themes Collection

A collection of custom themes for the MacDown markdown editor, focusing on modern design principles and readability.

## Available Themes

### Mou Night+ Modern v1
A modern take on the classic Mou Night+ theme, featuring:
- Radix UI inspired design elements
- Variable-based color system
- Modern spacing and typography
- Enhanced table styles
- Improved code blocks
- Print-friendly styles

## Installation

1. Clone this repository:
   ```bash
   git clone [repository-url]
   ```

2. Copy the desired theme file to MacDown's Styles directory:
   ```bash
   cp styles/[theme-name].css ~/Library/Application\ Support/MacDown/Styles/
   ```

3. In MacDown's preferences:
   - Go to the "Editor" tab
   - Select your installed theme from the "Theme" dropdown

## Theme Development

### CSS Variables

The themes use CSS variables for easy customization. Common variables include:

```css
--bg-primary: Main background color
--text-primary: Primary text color
--heading-color: Heading text color
--link-color: Link color
--code-color: Code text color
```

See individual theme files for complete variable lists.

### File Structure

```
.
├── README.md
├── styles/
│   └── [theme-name].css
└── .gitignore
```

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

MIT License
