

```markdown
# 👟 Shoe Inventory Manager

A modern and lightweight web app to manage and showcase your personal sneaker collection.  
Perfect for collectors, resellers, or anyone who wants to keep their kicks organized.

🎥 [Watch the video tutorial on YouTube](https://www.youtube.com/watch?v=Wgly7tYw2Ow&t=22s)

---

## ✨ Features

* 🖥️ **Responsive design** – works on desktop, tablet, and mobile  
* 🔍 **Live search** – filter by brand or model name in real time  
* 🧠 **Smart brand grouping** – shoes grouped by brand with logo or color  
* 🧮 **Live counter** – see how many shoes are currently displayed  
* 🧩 **Size & lace length legend** – handy info for quick access  
* 🎨 **Grid layout** – clean, image-first display  
* ⚡ **Vanilla JavaScript only** – no frameworks or dependencies  

---

## 📁 Project Structure

```

shoe-inventory/
├── index.html          # Main app file
└── img/                # Folder for all shoe images
├── shoe1.jpg
├── shoe2.jpg
└── ...

````

---

## 🚀 Getting Started

1. **Clone this repository**

   ```bash
   git clone https://github.com/yourusername/shoe-inventory.git
   cd shoe-inventory
````

2. **Add your images**

   * Put your sneaker images in the `img/` folder
   * Use JPG, PNG or WEBP – 300x300px recommended

3. **Update shoe list**

   * Open `index.html`
   * Find the JavaScript `shoes` array
   * Replace demo shoes with your own:

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
     // Add more...
   ];
   ```

4. **Add brand logos** (optional)
   Inside the `renderShoes()` function:

   ```javascript
   if (brand.toLowerCase().includes("nike")) {
     logo = "img/nike-logo.png";
   } else if (brand.toLowerCase().includes("adidas")) {
     logo = "img/adidas-logo.png";
   }
   ```

5. **Customize the legends**
   Update size and lace length references in the HTML if needed.

6. **Run it**
   Just double-click `index.html` – no server required.

---

## 🎥 Video Tutorial

Need help getting started?
Check out the step-by-step video guide on YouTube:

👉 [Watch the tutorial](https://www.youtube.com/watch?v=Wgly7tYw2Ow&t=22s)

It covers everything from setup to customization!

---

## 🧰 Customization

### ➕ Add a New Shoe

```javascript
{
  brand: "Puma",
  name: "Suede Classic Red",
  image: "img/puma-suede.jpg"
}
```

### 🏷️ Add a New Brand

1. Add at least one shoe with the new brand name
2. Optionally define a logo in `renderShoes()`
3. Adjust color or size legends if needed

### 🎨 Style It

Edit the `<style>` section in `index.html` to tweak:

* Color palette
* Fonts
* Grid spacing
* Card styling

---

## 🌐 Deployment

Ready to go live! Use any static site hosting:

* 📦 **GitHub Pages**
* ⚡ **Netlify**
* 🌍 **Vercel**
* ☁️ **Any static web host**

---

## 📱 Mobile Friendly

✅ Fully responsive:
Looks great on all screen sizes – tested on:

* Desktop
* Tablet
* Smartphone

---

## 📸 Image Guidelines

* 📐 **Ratio**: Square (e.g. 300x300px)
* 🧾 **File names**: Clear and lowercase (e.g. `nike-af1-white.jpg`)
* 📉 **Compression**: Optimize for web loading speed

---

## 💡 Pro Tips

1. Keep all images consistent in size and format
2. Use clear, bright photos
3. Organize by brand for quick navigation
4. Update your inventory regularly

---

## 🖼️ Logo Placeholder or Profile Photo

By default, a simple circular logo with a sneaker emoji is shown like this:

```html
<div style="margin: 0 auto 16px auto; width: 120px; height: 120px; background: #000001; border-radius: 50%; box-shadow: 0 2px 8px #0002; display: flex; align-items: center; justify-content: center; color: white; font-size: 24px; font-weight: bold;">
  👟
</div>
```

---

### 🧑‍🎨 Want to use your own photo or logo instead?

Replace the placeholder above with this image tag:

```html
<img src="img/your-photo.jpg" 
     alt="Logo" 
     style="display:block; 
            margin:0 auto 16px auto; 
            width:120px; 
            height:120px; 
            object-fit:contain; 
            border-radius:50%; 
            box-shadow:0 2px 8px #0002;">
```

✔️ Put your image inside the `img/` folder
✔️ Use a square image like `your-photo.jpg`

---

## 📄 License

MIT License – Free to use, modify and distribute.

---

**Disclaimer**: The shoe brands and models shown in the demo are fictional and for illustrative purposes only.

```

---


