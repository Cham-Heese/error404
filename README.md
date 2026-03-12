# error404
This is a comprehensive README.md file for your "Error404 - Digital Solutions" website project, formatted for GitHub.
```markdown
# Error404 - Digital Solutions


A modern, responsive HTML website for a general IT consulting company. Built with clean design principles, soft animations, and a focus on user experience.

## 🚀 Live Demo

[View Live Demo](#) *(https://cham-heese.github.io/error404/)*

## 📋 Features

- **Responsive Design** — Works flawlessly on desktop, tablet, and mobile devices
- **Soft, Modern UI** — Mild color palette with orange accents, subtle shadows, and smooth transitions
- **Interactive Elements** — Pulsing hover effects on navigation, cards, and buttons
- **Single-Page Architecture** — All content organized in one page with anchor navigation
- **Service Sections** — Dedicated areas for each core offering with stock photography
- **Clickable Service Cards** — Each card links directly to its detailed section
- **Custom Text Logo** — Distinctive "404" badge with company name
- **Photo Gallery** — Stock imagery showing servers, engineers, and workspace scenarios
- **Smooth Scrolling** — Anchor links provide smooth navigation between sections

## 🛠️ Technologies Used

- HTML5
- CSS3 (custom properties, animations, flexbox, grid)
- Google Fonts (Inter)
- Unsplash Stock Photography
- No external dependencies or frameworks

## 📁 Project Structure

```
error404-digital-solutions/
│
├── index.html          # Main website file
├── README.md           # Project documentation
```

## 🎨 Color Palette

| Color | Hex | Usage |
|-------|-----|-------|
| Muted Denim | `#5b7a9a` | Primary accents, card headings |
| Orange Brand | `#d97c4a` | Highlights, hover effects, logo |
| Soft Dark | `#2e445b` | Headlines, primary text |
| Text Soft | `#4d6278` | Body text, secondary information |
| Border Soft | `#e4edf5` | Card borders, dividers |
| Background | `#fafafa` | Page background |

## 🔧 Customization

### Changing Stock Photos

The website uses Unsplash images via URLs. To replace any image:

1. Find a new image on [Unsplash](https://unsplash.com)
2. Copy the image URL with `&w=800&q=80` parameters for optimal loading
3. Replace the `src` attribute in the respective `<img>` tag

### Modifying Colors

Colors are defined as CSS custom properties in the `:root` selector. Edit the values to match your brand:

```css
:root {
  --orange-brand: #d97c4a;  /* Change this for different accent color */
  --primary-mild: #5b7a9a;  /* Primary blue tone */
  /* ... other variables */
}
```

### Adding New Sections

1. Copy an existing `<section>` block
2. Update the `id` attribute to match your anchor link
3. Add a corresponding menu item in the navigation
4. Update content and images as needed

## 📱 Responsive Breakpoints

- **Desktop**: 1280px+ (max container width)
- **Tablet**: 800px (navigation and grid adjustments)
- **Mobile**: Below 800px (stacked layout)

## 🔗 Navigation Structure

The site uses anchor links for smooth single-page navigation:

- `#home` — Hero section
- `#it-consulting` — IT Consulting details
- `#networks` — Networks section
- `#workspaces` — Digital Workspaces
- `#cloud` — Cloud Computing
- `#contact` — Contact information

## ✨ Key Interactions

- **Navigation Hover** — Pulsing glow effect with orange accent
- **Service Cards** — Lift animation with orange shadow pulse on hover
- **Photo Cards** — Gentle lift with border color change
- **CTA Buttons** — Scale and shadow effects on hover
- **Smooth Scrolling** — CSS `scroll-behavior: smooth` for anchor links

## 📝 Grammar and Style Notes

- Headers use title case for stylistic preference
- "IT" is consistently capitalized throughout
- Body text follows standard English grammar
- Service names maintain consistent capitalization

## 🖼️ Image Credits

All stock photos are sourced from [Unsplash](https://unsplash.com):

- Business meeting: [Unsplash](https://unsplash.com/photos/people-sitting-on-chairs-inside-room-5fNmWej4tAA)
- Server room: [Unsplash](https://unsplash.com/photos/black-and-silver-server-racks-2LowH3j0KPM)
- Network switches: [Unsplash](https://unsplash.com/photos/black-and-white-server-racks-wXiTjpPjQv4)
- Engineer with tablet: [Unsplash](https://unsplash.com/photos/man-in-blue-long-sleeve-shirt-holding-black-android-smartphone-KdeqA3aTnBY)
- Workspace with laptop: [Unsplash](https://unsplash.com/photos/person-using-macbook-pro-on-brown-wooden-table-5fNmWej4tAA)
- Cloud concept: [Unsplash](https://unsplash.com/photos/blue-and-white-satellite-dish-3SfG9QOq2mk)

## 🚦 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/error404-digital-solutions.git
   ```

2. **Open the website**
   - Navigate to the project folder
   - Open `index.html` in your browser

3. **Deploy to GitHub Pages**
   - Push to your GitHub repository
   - Go to Settings → Pages
   - Select main branch as source
   - Your site will be published at `https://yourusername.github.io/error404-digital-solutions`

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](#).

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Contact

**Error404 - Digital Solutions**  
- Email: hello@error404.digital 
- Website: [www.error404.digital](#) 
- GitHub: [@cham-heese](#)

---

*Designed with ❤️ for modern IT consulting*
 
