## Frontend Basics - Lab gi3
## Burakov Stanislav IP-34

A simple static project demonstrating two page layouts of the same UI using classic CSS techniques: float-based layout and a flex/absolute-based layout.

### Project Description

The project showcases how the same block layout can be implemented with different CSS approaches:

- **Float Layout**: Implemented in `index.html` with `styles.css`
- **Flex Layout**: Implemented in `flex-layout.html` with `flex-styles.css`

Each page renders a 1000×800 container composed of five colored blocks:
- **Left Block (IMG)**
- **Top Block (TEXT)**
- **Middle Block (IMG)**
- **Far Right Block (TEXT)**
- **Bottom Block (TEXT)**

Navigation links let you switch between the float and flex pages. Text content is in Ukrainian.

### Features

- **Two CSS approaches**: Compare float-based vs flex/absolute positioning
- **Consistent layout**: Identical block composition across pages for easy comparison
- **Centered labels**: Blocks center their label content for clarity
- **Simple navigation**: Links between pages for quick switching

### Project Structure

```
.
├── index.html                 # Float-based layout page
├── styles.css                 # Styles for float layout
├── flex-layout.html           # Flex/absolute layout page
└── flex-styles.css            # Styles for flex/absolute layout
```

### How to Run Locally

No build tools required. Open the HTML files directly in a browser.

1. Open the project folder
2. Open a page:
   - Double-click `index.html` for the float layout
   - Or open `flex-layout.html` for the flex/absolute layout
3. Switch pages using the link at the bottom of each page.

### Browser Support

Works in all modern browsers:
- Chrome (latest)
- Firefox (latest)
- Edge (latest)
- Safari (latest)

### Troubleshooting

- If styles don’t appear, confirm `styles.css` or `flex-styles.css` is in the same directory as the HTML file
- If links don’t work, ensure you opened the file paths exactly as listed and remain within the same folder
- If caching is suspected, hard-refresh the page (Ctrl+F5)


