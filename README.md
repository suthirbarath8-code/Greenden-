# 🌸 Greenden: Responsive Flower Décor Website

A fully responsive flower décor website built with **HTML** and **Tailwind CSS**. It includes a Home page, a Products page, and a Contact page, and it works smoothly on mobile, tablet, and desktop.

---

## ✨ Features

- Large assortment of floral décor products
- Free and fast shipping highlight section
- 24/7 customer support section
- Customer reviews section
- Products page with responsive product cards
- Contact page with a validated form
- Mobile-friendly navigation menu
- Clean, soft, floral color theme
- No build tools required (uses Tailwind CDN)

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| HTML5 | Page structure |
| Tailwind CSS (CDN) | Styling and responsiveness |
| Vanilla JavaScript | Mobile menu toggle |

---

## 📁 Project Structure

```
flower-decor-website/
│
├── index.html          # Home page
├── products.html       # Products page
├── contact.html        # Contact page
├── README.md           # Project documentation
│
└── images/
    ├── flower-1.jpg
    ├── flower-2.jpg
    ├── flower-3.jpg
    └── ...
```

---

## 🚀 Getting Started

### 1. Download or clone the project

```bash
git clone https://github.com/your-username/flower-decor-website.git
cd flower-decor-website
```

### 2. Open in browser

Double-click `index.html`, or use the Live Server extension in VS Code.

No installation is needed. Tailwind CSS loads from the CDN:

```html
<script src="https://cdn.tailwindcss.com"></script>
```

> **Note:** The CDN is great for development and small sites. For a live production site, install Tailwind with the CLI for better performance.

---

## 📄 Pages Overview

### 🏠 Home (`index.html`)
- Hero banner with a call-to-action button
- Three highlight sections:
  - **Large Assortment**: a wide range of bouquets, centerpieces, and seasonal arrangements
  - **Free and Fast Shipping**: free delivery with careful packaging
  - **24/7 Support**: help available any time of day
- Featured products
- Customer reviews (Our Work, Transaction, Shipment)

### 🛍️ Products (`products.html`)
- Responsive grid: 1 column on mobile, 2 on tablet, 3-4 on desktop
- Each card includes an image, name, short description, price, and an "Add to Cart" button
- Hover effects on cards

### 📞 Contact (`contact.html`)
- Contact form with name, email, phone, and message fields
- Business details: address, phone, email, working hours
- Embedded map placeholder
- 24/7 support note

---

## 🌼 Product List

| # | Product Name | Image File |
|---|--------------|------------|
| 1 | Blush Rose Bloom | `flower-1.jpg` |
| 2 | Soft Peach Roses | `flower-2.jpg` |
| 3 | Golden Ivory Charm | `flower-3.jpg` |
| 4 | Pink Tulip Glow | `flower-4.jpg` |
| 5 | Porch Garden Mix | `flower-5.jpg` |
| 6 | Spring Tulip Joy | `flower-6.jpg` |
| 7 | Citrus Tulip Fresh | `flower-7.jpg` |
| 8 | Ivory Garden Bliss | `flower-8.jpg` |
| 9 | Green Hydrangea Haven | `flower-9.jpg` |
| 10 | Ribbon Rose Posy | `flower-10.jpg` |
| 11 | Chartreuse Peony Charm | `flower-11.jpg` |

---

## 🧩 Sample Product Card

```html
<div class="overflow-hidden rounded-2xl bg-white shadow-lg transition hover:-translate-y-1 hover:shadow-xl">
  <img src="images/flower-1.jpg" alt="Blush Rose Bloom" class="h-64 w-full object-cover">
  <div class="p-5">
    <h3 class="text-lg font-bold text-rose-700">Blush Rose Bloom</h3>
    <p class="mt-1 text-sm text-stone-500">Soft pink roses in a white ceramic vase.</p>
    <div class="mt-4 flex items-center justify-between">
      <span class="text-xl font-semibold">₹999</span>
      <button class="rounded-full bg-rose-600 px-4 py-2 text-sm text-white hover:bg-rose-700">
        Add to Cart
      </button>
    </div>
  </div>
</div>
```

---

## 📱 Responsive Breakpoints

| Device | Tailwind Prefix | Screen Width |
|--------|-----------------|--------------|
| Mobile | (default) | < 640px |
| Tablet | `md:` | ≥ 768px |
| Laptop | `lg:` | ≥ 1024px |
| Desktop | `xl:` | ≥ 1280px |

---

## 🎨 Customization

**Change brand colors:** Replace the `rose` classes (for example `bg-rose-600`) with any Tailwind color such as `pink`, `fuchsia`, or `emerald`.

**Change fonts:** Add a Google Font in the `<head>` and configure it:

```html
<script>
  tailwind.config = {
    theme: { extend: { fontFamily: { display: ['Playfair Display', 'serif'] } } }
  }
</script>
```

**Add new products:** Copy a product card in `products.html`, then update the image, name, description, and price.

---

## 🌐 Deployment

You can host this site for free on:

- **GitHub Pages**: Settings → Pages → select the main branch
- **Netlify**: drag and drop the project folder
- **Vercel**: import the repository

---

## ✅ To-Do / Future Improvements

- [ ] Shopping cart functionality
- [ ] Product search and category filters
- [ ] Online payment integration
- [ ] Backend for the contact form (Formspree, EmailJS, or Node.js)
- [ ] Customer login and order tracking

---

## 📬 Contact

- **Email:** support@yourflowerstore.com
- **Phone:** +91 00000 00000
- **Support:** Available 24/7

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

---

Made with 🌷 and Tailwind CSS
