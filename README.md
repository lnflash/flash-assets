# Flash Assets

A comprehensive collection of brand and design assets for Flash - a Bitcoin Lightning wallet application. This repository contains all visual assets including logos, icons, marketing materials, and documentation resources.

## 📁 Repository Structure

The assets are organized into five main categories for easy navigation:

### 01-brand-assets/
Core brand identity elements that define Flash's visual identity.

- **logos/** - Primary Flash logos in various formats
  - Main Flash logos (PNG, SVG)
  - White variants for dark backgrounds
  - QR code variations
- **colors/** - Brand color definitions
  - `light.css` - Light theme color palette
- **typography/** - Font files and typography styles
  - Roboto font files (TTF, WOFF)
  - Typography CSS definitions

### 02-product-assets/
Assets used directly in the Flash application.

- **app-icons/** - Application icons for different platforms
  - `dark/` - Dark theme app icons (72x72 to 512x512)
  - `light/` - Light theme app icons
  - `mono-dark/` - Monochrome dark variants
  - `mono-light/` - Monochrome light variants
- **favicons/** - Website favicons with theme variants
  - Each theme includes: favicon.ico, PNG sizes, Apple touch icons, and web manifests
- **ui-icons/** - User interface icons (SVG format)
  - Payment icons (send, receive, lightning)
  - Navigation icons (arrows, menu, home)
  - Action icons (copy, share, scan)
  - Status icons (success, error, warning)

### 03-marketing-assets/
Materials for marketing and promotional use.

- **graphics/** - Marketing graphics and illustrations
  - `raster/` - PNG images (bitcoin concepts, mobile app previews)
  - `vector/` - SVG graphics (confetti, stream)
- **backgrounds/** - Background images for marketing materials
  - Cloud backgrounds (PNG)
  - Stream backgrounds (PNG, WEBP)
- **flashcards/** - Physical flashcard designs
  - Various sizes for beach, car, market themes
- **badges/** - App store and platform badges
  - `raster/` - PNG versions
  - `vector/` - SVG versions
- **stickers/** - Bitcoin advocacy sticker designs
  - "Bitcoin accepted here" variations
  - Educational stickers
  - Warning/caution designs
- **social-media/** - Social media platform icons
  - Facebook, GitHub, Instagram, Twitter, Nostr

### 04-documentation/
Documentation and development resources.

- **screenshots/** - Application screenshots
  - Tutorial screenshots
  - Feature demonstrations
  - `v0.4.0/` - Version-specific screenshots
- **storybook/** - Storybook documentation files
  - MDX story files for each asset category
  - Component documentation
  - Style definitions

### 05-third-party/
External brand assets for integrations.

- **wallet-logos/** - Logos of compatible Bitcoin wallets
  - Blue Wallet, Breez, Muun, Phoenix, Satoshi

## 🚀 Getting Started

### Viewing Assets with Storybook

This repository includes Storybook for browsing and documenting assets:

```bash
# Install dependencies
npm install

# Run Storybook
npm run storybook
```

Visit `http://localhost:6006` to browse assets interactively.

### Using Assets

1. **For Development**: Reference assets directly from their organized folders
2. **For Marketing**: Find print-ready materials in `03-marketing-assets/`
3. **For App Integration**: Use appropriately sized assets from `02-product-assets/`

## 📏 Asset Guidelines

### App Icons
- Available in standard sizes: 72x72, 96x96, 128x128, 144x144, 152x152, 192x192, 384x384, 512x512
- Four theme variants: dark, light, mono-dark, mono-light

### UI Icons
- Primarily SVG format for scalability
- Consistent style and stroke width
- Named descriptively for easy identification

### Color Themes
- Defined in CSS for easy integration
- Currently includes light theme with plans for dark theme

## 🤝 Contributing

When adding new assets:
1. Place them in the appropriate category folder
2. Follow existing naming conventions
3. Include multiple sizes/formats when applicable
4. Update relevant Storybook documentation

## 📄 License

MIT License - See package.json for details

## 🔗 Related Projects

- [Flash Wallet](https://github.com/lnflash/flash-mobile) - The main Flash wallet application
- [Flash Documentation](https://docs.getflash.io) - User and developer documentation

---

For questions or support, please open an issue or contact the Flash team.
