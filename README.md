# Hugo Links Shortcode

A simple, clean shortcode to display a collection of important links in your Hugo blog posts.

![Example screenshot](https://github.com/user-attachments/assets/5b3c3e6c-d5ff-4fdd-8d40-7e041c2879f1)


## Features
- Clean, minimal design
- Hover effects
- Mobile responsive
- No external dependencies
- Easy to customize

## Installation

1. Create a new file `layouts/shortcodes/links.html` in your Hugo project
2. Copy the provided code into this file
3. Customize the links in the HTML section of the shortcode

```html
<div class="links">
    <a href="your-url" class="link-item">Link Text</a>
    <!-- Add more links as needed -->
</div>
```

## Usage

In any markdown file, use the shortcode:

```markdown
{{< links >}}
```

## Customization

The default color scheme uses blue (#2563eb). To change the color, modify these values in the CSS:
- `border: 2px solid #2563eb;` (link border)
- `color: #2563eb;` (link text)
- `background-color: #2563eb;` (hover state)

## License

MIT
