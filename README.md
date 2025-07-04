Ecco una descrizione completa in inglese per GitHub:

## 👟 Shoe Inventory Manager

A modern web application to manage and display your personal shoe collection. Perfect for collectors, resellers, or anyone who wants to keep track of their footwear in an organized way.

### ✨ Features

- **Intuitive interface** with responsive design
- **Brand filtering** to easily navigate through different brands
- **Real-time search** by name or brand
- **Automatic counter** of displayed shoes
- **Brand organization** with colored logos
- **Grid layout** optimized for visualization
- **Size and lace legend** for quick reference
- **Pure vanilla JavaScript** - no dependencies

### 🚀 Demo

The demo includes fictional brands and models for demonstration purposes:
- SkyStep, UrbanMax, FlexFit, TrailRun, StreetStyle, ClassicWear, SportMax

### 📁 Project Structure

```
shoe-inventory/
├── index.html          # Main application file
└── img/               # Folder for shoe images
    ├── shoe1.jpg
    ├── shoe2.jpg
    └── ...
```

### 🛠️ Setup & Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/shoe-inventory.git
   cd shoe-inventory
   ```

2. **Add your shoe images**
   - Place your shoe images in the `img/` folder
   - Supported formats: JPG, PNG, WEBP
   - Recommended size: 300x300px or similar square ratio

3. **Update your shoe data**
   - Open `index.html` in a text editor
   - Find the `shoes` array in the JavaScript section
   - Replace the demo data with your shoes:

   ```javascript
   let shoes = [
     { 
       brand: "Nike", 
       name: "Air Force 1 White", 
       image: "img/af1-white.jpg" 
     },
     { 
       brand: "Adidas", 
       name: "Stan Smith Green", 
       image: "img/stan-smith.jpg" 
     },
     // Add more shoes...
   ];
   ```

4. **Customize brand logos** (optional)
   - In the `renderShoes()` function, find the brand logo section
   - Add your brand logos or customize the colored placeholders:

   ```javascript
   // Add custom logos
   if (brand.toLowerCase().includes('nike')) logo = 'img/nike-logo.png';
   else if (brand.toLowerCase().includes('adidas')) logo = 'img/adidas-logo.png';
   ```

5. **Update size and lace legends**
   - Modify the legend sections in the HTML to match your shoe sizes
   - Update lace lengths according to your shoe models

6. **Open in browser**
   - Simply open `index.html` in your web browser
   - No server required!

### 🎯 Customization Guide

#### Adding New Shoes
```javascript
// Add to the shoes array
{ 
  brand: "Your Brand", 
  name: "Model Name", 
  image: "img/your-image.jpg" 
}
```

#### Adding New Brands
1. Add shoes with the new brand name
2. Optionally add a logo in the brand rendering section
3. Update the size legend if needed

#### Styling
- Modify CSS variables in the `<style>` section
- Change colors, fonts, spacing as needed
- All styling is contained in the HTML file

### 🌐 Deployment

Easy to deploy on:
- **GitHub Pages**: Push to `gh-pages` branch
- **Netlify**: Drag and drop the folder
- **Vercel**: Connect your GitHub repository
- **Any static hosting**: Upload the files

### 📱 Responsive Design

Fully responsive and works perfectly on:
- Desktop computers
- Tablets
- Mobile phones

### 🎨 Tech Stack

- **HTML5**: Structure and content
- **CSS3**: Styling with Flexbox and Grid
- **Vanilla JavaScript**: Functionality and interactivity
- **No external dependencies**: Self-contained and fast

### 🔧 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Any modern browser with JavaScript enabled

### 📸 Image Guidelines

- **Format**: JPG, PNG, or WEBP
- **Size**: 300x300px recommended (square ratio)
- **File naming**: Use descriptive names (e.g., `nike-af1-white.jpg`)
- **Compression**: Optimize images for web to reduce loading times

### 🎯 Tips for Best Results

1. **Consistent image sizes** for better layout
2. **Clear, well-lit photos** for better visibility
3. **Descriptive names** for easy searching
4. **Organize by brand** for better navigation
5. **Regular updates** to keep inventory current

---

**Note**: The brands and models in the demo are completely fictional and created for demonstration purposes only.

### 🤝 Contributing

Feel free to submit issues, feature requests, or pull requests to improve the application!

### 📄 License

MIT License - feel free to use and modify as needed.



**IMAGE SNEAKER INVENTORY**: If you want photo in the pro pic and not the shoes with the color use this following code

*/  <img src="img/" alt="Logo" style="display:block;margin:0 auto 16px auto;width:120px;height:120px;object-fit:contain;border-radius:50%;box-shadow:0 2px 8px #0002;"> /*
