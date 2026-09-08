# PRECISION DETAILING — Premium Responsive HTML/CSS Template

Thank you for purchasing the Precision Detailing Template! This modern, high-converting template is designed specifically for mobile auto detailing, valeting, and trade services.

---

## 🛠️ Included Files
* `index.html` — Main website structure, content, and interactive JavaScript logic.
* `style.css` — Complete stylesheet including CSS custom variables, layout grids, and responsive media queries.
* `README.md` — Setup instructions and customization guide.

---

## ⚡ Quick Start Guide

### 1. How to Edit Text & Pricing
Open `index.html` in any text editor (VS Code, Notepad, Sublime Text) to customize your business details:
* **Business Name & Logo:** Search for `logo` (Line 18) and replace `PRECISION` with your company name.
* **Pricing & Services:** Search for `id="packages"` (Line 60) to modify package titles, bullet points, and baseline prices.
* **Contact Phone:** Search for `tel:07000000000` (Line 48) and swap it with your business phone number.

### 2. Setting Up the Booking Form
To receive booking requests directly to your email inbox:
1. Sign up for a free account at [Formspree](https://formspree.io) or [Web3Forms](https://web3forms.com).
2. Get your custom form endpoint URL.
3. Open `index.html`, find `<form class="booking-form" action="#" ...>`, and replace `action="#"` with your form endpoint URL:
   ```html
   <form class="booking-form" action="[https://formspree.io/f/YOUR_FORM_ID](https://formspree.io/f/YOUR_FORM_ID)" method="POST">

    