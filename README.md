# Product Preview Card (Vanilla Web)

A clean, responsive Product Preview Card component built using vanilla HTML and CSS.

![Product Preview](./images/active-states.jpg)

## Key Features & Benefits

- **Clean and Simple:** Built using only vanilla HTML and CSS for a lightweight, dependency-free component.
- **Responsive Design:** Uses separate mobile and desktop hero images and responsive layout for good viewing on small and large screens.
- **Easy to Integrate:** Drop the `index.html`, `style.css`, and the `images/` folder into any project—no build step required.
- **Customizable:** Simple class structure lets you change copy, images, and styles quickly.

## Prerequisites & Dependencies

- A web browser (Chrome, Firefox, Safari) to view the component.
- A text editor or IDE to edit `index.html` and `style.css` (e.g., VS Code).

## Installation & Setup Instructions

1. **Clone or download the repository** (or copy the project folder locally):

```bash
git clone https://github.com/syntaxSangoma/product-preview-card-vanilla-04
```

```bash
cd product-preview-card-04
```

2. **Open the project** in your editor and open `index.html` in the browser:

- Double-click `index.html` or open it from your editor.
- Or serve the folder using a simple local server (recommended for consistent image loading)

## Usage Examples

The component is static and intended as a product preview card. To modify content, edit `index.html`:

- Replace hero images at `./images/image-product-mobile.jpg` and `./images/image-product-desktop.jpg` with your own images.
- Update the product name, category, description, and prices directly in the markup.
- Change the cart icon at `./images/icon-cart.svg` if desired.

Example: update the product price in the `.product-card__price-group` markup to show your own sale price.

## Configuration Options

Most visual changes live in `style.css`. Typical customizations:

- **Colors & Palette:** Edit color values in `style.css` (or add CSS variables at the top) to change the theme.
- **Typography:** Change the `font-family` or import a Google Font in `style.css`.
- **Card Size & Spacing:** Tweak `.product-card` width, padding, and image sizes to fit your layout.
- **Buttons & Interaction:** Update `.product-card__addToCart` styles for hover, active and focus states.

## Contributing Guidelines

Contributions are welcome. Suggested flow:

1. Fork the repository.
2. Create a feature branch (e.g., `feature/add-dark-mode`).
3. Make changes with focused commits.
4. Push to your fork and open a pull request describing your changes.

## License

License not specified.

## Acknowledgments

- Google Fonts for the ``Montserrat`` and ``Fraunces`` font used in this project.
