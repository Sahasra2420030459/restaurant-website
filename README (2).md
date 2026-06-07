# Savor & Sage Restaurant Website

> A modern, responsive restaurant website with menus, reservations, and event details to enhance the customer dining experience.

**[Live Demo](https://your-restaurant-demo-link.com)** | **[Portfolio](https://github.com/yourusername)**

---

## What This Is

A fully responsive, multi-page restaurant website built with pure HTML, CSS, and JavaScript:

1. **Beautiful Home Page** - Hero section, features, and chef's specialties preview
2. **Complete Menu** - Categorized food items with prices in Indian Rupees (₹)
3. **Online Reservations** - Interactive booking form with validation
4. **Events & Experiences** - Special dining events with pricing
5. **About & Contact** - Restaurant story, team, and contact details
6. **Mobile Responsive** - Works perfectly on phones, tablets, and desktops

Built for restaurant owners who want an elegant online presence without complex frameworks.

---

## Features

| Feature | Status |
|---------|--------|
| Responsive Hero Section | Done |
| Interactive Navigation (Mobile Hamburger) | Done |
| Full Menu with Categories | Done |
| Online Reservation Form | Done |
| Events & Special Experiences | Done |
| Customer Reviews Section | Done |
| Contact & About Page | Done |
| Scroll Animations | Done |
| Sticky Navigation | Done |
| Footer with Quick Links | Done |

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | HTML5, CSS3, JavaScript (Vanilla) |
| Styling | CSS Variables, Flexbox, CSS Grid |
| Icons | Font Awesome 6.4.0 |
| Images | Unsplash (Free Stock Photos) |
| Fonts | Google Fonts (Georgia, Segoe UI) |
| Deployment | GitHub Pages / Netlify / Vercel |

---

## Run Locally

**Requirements:** Any modern web browser (Chrome, Firefox, Edge, Safari)

**1. Clone**

```bash
git clone https://github.com/yourusername/restaurant-website.git
cd restaurant-website
```

**2. Open in Browser**

Simply double-click `index.html` or use a live server:

```bash
# Using VS Code Live Server extension
# Right-click index.html → "Open with Live Server"

# Or using Python
python -m http.server 8000
```

**3. View**

Open http://localhost:8000 or just double-click `index.html`

---

## How to Use

1. **Home Page** (`index.html`) - Explore the restaurant highlights and chef's specialties
2. **Menu** (`menu.html`) - Browse appetizers, main courses, and desserts with prices
3. **Reservations** (`reservations.html`) - Book a table online with date/time selection
4. **Events** (`events.html`) - Discover special dining experiences and pricing
5. **About** (`about.html`) - Learn the restaurant story and contact details

**Navigation:**

- All pages are connected via the sticky navigation bar
- Mobile users can use the hamburger menu (three lines)
- Active page is highlighted in the navigation

---

## Repository Structure

```
.
├── index.html              # Home page
├── menu.html               # Full menu page
├── reservations.html       # Table booking page
├── events.html             # Special events page
├── about.html              # About & contact page
├── css/
│   └── style.css           # All styles (colors, layout, animations)
├── js/
│   └── script.js           # Interactive features (mobile menu, form, scroll)
├── images/                 # Local images (optional)
└── README.md               # This file
```

---

## Customization

### Change Restaurant Name

Search and replace `"Savor & Sage"` in all HTML files with your restaurant name.

### Change Colors

Edit `css/style.css`:

```css
:root {
  --primary-color: #c0392b;    /* Main brand color */
  --accent-color: #f39c12;     /* Highlights & buttons */
  --secondary-color: #2c3e50;  /* Text headings */
}
```

### Change Prices

Edit prices directly in `menu.html` and `events.html`:

```html
<span class="price">₹1,299</span>
```

### Add Real Photos

Replace Unsplash URLs with your own images:

```html
<div class="menu-item-image" style="background-image: url('images/your-photo.jpg');"></div>
```

---

## Pages Overview

### Home Page (`index.html`)
- Full-screen hero with call-to-action buttons
- "Why Choose Us" feature cards
- Chef's specialties preview
- Footer with contact info and hours

### Menu Page (`menu.html`)
- Appetizers, Main Courses, Desserts sections
- Each item has photo, name, price, and description
- Hover effects on menu cards

### Reservations (`reservations.html`)
- Form with name, email, phone, date, time, guests
- Special occasion selection
- Success message on submission
- Contact cards for phone/email

### Events (`events.html`)
- 6 upcoming events with dates and pricing
- Event cards with images and descriptions
- Private events inquiry section

### About (`about.html`)
- Restaurant story and philosophy
- Team member profiles
- Contact information and hours

---

## Deployment

### GitHub Pages (Free)

1. Push code to GitHub repository
2. Go to **Settings → Pages**
3. Select branch: `main`, folder: `/ (root)`
4. Your site will be live at `https://yourusername.github.io/restaurant-website`

### Netlify (Free)

1. Drag and drop your project folder to [netlify.com](https://netlify.com)
2. Get instant live URL

### Vercel (Free)

1. Install Vercel CLI: `npm i -g vercel`
2. Run: `vercel` in project folder
3. Follow prompts to deploy

---

## Browser Support

| Browser | Support |
|---------|---------|
| Chrome | ✅ Full |
| Firefox | ✅ Full |
| Safari | ✅ Full |
| Edge | ✅ Full |
| Mobile Chrome | ✅ Full |
| Mobile Safari | ✅ Full |

---

## Future Enhancements

- [ ] Online food ordering system
- [ ] Customer review submission form
- [ ] Photo gallery page
- [ ] Dark mode toggle
- [ ] Newsletter signup
- [ ] Google Maps integration
- [ ] Multi-language support
- [ ] Admin dashboard for menu updates

---

## Author

**Your Name** - Web Developer

GitHub: [yourusername](https://github.com/yourusername) | Email: your.email@example.com

---

## License

MIT
