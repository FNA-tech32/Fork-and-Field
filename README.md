# Fork&Field — Hotel & Restaurant

Welcome to the official website repository for **Fork&Field**, a premier culinary haven and hotel experience located in Hamirpur, Himachal Pradesh. Fork&Field combines authentic Indian traditions, continental flavors, signature thalis, and comfortable AC & Non-AC hotel accommodations.

---

## 🍽️ About Fork&Field

Located at Kehdru Bus Stop, Hamirpur, **Fork&Field** is dedicated to quality ingredients, delightful flavors, and attentive hospitality. Whether guests are visiting for a family dinner, highway rest stop, private event, or an overnight stay, Fork&Field delivers a warm, memorable experience.

- **Cuisine:** North Indian, South Indian, Breakfast Specials, Chinese, Street Food & Snacks, Beverages, and Signature Thalis.
- **Stay:** Well-appointed AC & Non-AC rooms with modern amenities, 24/7 service, and free Wi-Fi.

---

## 📞 Contact Information & Location

| Detail | Information |
| :--- | :--- |
| **Brand Name** | **Fork&Field** |
| **Address** | Kehdru Bus Stop, Kehdru, Hamirpur, Himachal Pradesh 177001, India |
| **Primary Phone** | [+91 088944 17262](tel:+9108894417262) |
| **Alternative Contact 1** | [+91 8219997479](tel:+918219997479) |
| **Alternative Contact 2** | [+91 8755831172](tel:+918755831172) |
| **Email (Inquiries)** | [contact@forkandfield.com](mailto:contact@forkandfield.com) |
| **Email (General)** | [info@forkandfield.com](mailto:info@forkandfield.com) |
| **Operating Hours** | 07:00 AM – 11:00 PM (Monday – Sunday, Open all 7 days) |

---

## ✨ Features & Website Highlights

1. **Responsive Navbar & Hero Slider**
   - High-resolution SVG brand identity (`fork_and_field_logo.svg`).
   - Fullscreen carousel with highlights of dining and room experiences.
   - Smooth navigation links with mobile-friendly collapse menu.

2. **Interactive Food Menu**
   - Tabbed menu navigation (Indian, Breakfast, Non-Veg, Snacks, Drinks).
   - Detailed dish listings with photos, descriptions, and transparent pricing.
   - Direct PDF brochure/menu download option.

3. **Signature Fork&Field Thali Showcase**
   - Special Veg Thali (₹230) and Non-Veg Thali (₹280).
   - Clear breakdown of included items (Dal Makhani, Karahi Paneer / Chicken Curry, Rice, Rotis, Raita, Salad, Achar).

4. **Hotel Rooms & Amenities**
   - Gallery showcasing deluxe rooms and stay facilities.
   - Highlights: 24/7 Room Service, High-speed Wi-Fi, Air Conditioning, Hygiene-first housekeeping.

5. **Customer Reviews Carousel**
   - Interactive review slider powered by MDB Carousel and Font Awesome star ratings.

6. **Online Reservation & Contact Form**
   - Instant inquiry form with validation.
   - Asynchronous submission powered by Fetch API and [FormSubmit](https://formsubmit.co/).
   - User-friendly success and error notifications.

7. **Interactive Google Map**
   - Embedded Google Map providing accurate navigation directly to the property in Kehdru.

---

## 📂 Project Structure

```text
Fork&Field/
├── assets/
│   ├── css/
│   │   └── style.css                     # Custom styles and responsive layouts
│   ├── js/
│   │   └── main.js                       # Animations, owl-carousel, and sticky navbar logic
│   ├── lib/                              # Vendor animation and icon libraries (WOW.js, etc.)
│   ├── menu/                             # High-res dish photographs
│   ├── Gallery_/                         # Room and restaurant photo gallery
│   ├── favicon.svg                       # Browser tab icon
│   ├── fork_and_field_logo.svg           # Vector brand logo for navbar
│   └── menu-final.pdf                    # Printable full menu brochure
├── default.php                           # Hostinger server redirect to index.html
├── index.html                            # Main website landing page
├── README.md                             # Project documentation
└── script.js                             # Custom client scripts
```

---

## 🚀 Getting Started & Local Development

No heavy build tools or Node dependencies are required. The website is built using lightweight standard modern web technologies.

### Option 1: VS Code Live Server (Recommended)
1. Open this project directory in [Visual Studio Code](https://code.visualstudio.com/).
2. Install the **Live Server** extension (`ritwickdey.liveserver`).
3. Right-click `index.html` and select **"Open with Live Server"**.
4. The site will automatically open in your browser at `http://127.0.0.1:5500`.

### Option 2: Python Built-in Server
Open a terminal in the project directory and run:
```bash
python -m http.server 8000
```
Then visit `http://localhost:8000` in your web browser.

### Option 3: PHP Built-in Server
If PHP is installed:
```bash
php -S localhost:8000
```
Then visit `http://localhost:8000`.

---

## 🌐 Deployment

### Hostinger / cPanel Web Hosting
1. Compress all files in the project folder (or upload via FTP / File Manager).
2. Upload the files into the `public_html` directory of your web host.
3. The included `default.php` automatically forwards visitors to `index.html`.

### Netlify / Vercel / GitHub Pages
- **GitHub Pages:** Go to repository settings > Pages > Branch `main` > `/root` > Save.
- **Vercel / Netlify:** Import the repository or drag-and-drop the directory directly.

---

## ⚙️ Configuration & Customization

- **Change Contact Form Recipient:**
  In `index.html` (around line 975), update the form action URL:
  ```html
  <form id="contactForm" action="https://formsubmit.co/YOUR_EMAIL@domain.com" method="POST">
  ```
- **Update Menu Items or Prices:**
  Locate the `#Menu` section in `index.html` and modify the dish titles, descriptions, and price spans.
- **Update Phone Numbers:**
  Update the `tel:` links in both the `#ContactUs` section and `<footer>` of `index.html`.

---

## 📄 License & Credits

- **Brand:** Fork&Field (Hotel & Restaurant)
- **Design & Solutions:** Digi India Solutions
- **License:** Proprietary & Confidential. All rights reserved by Fork&Field.
