# Auto Repair & Maintenance Garage Website Template

A premium, high-converting, mobile-responsive landing page template custom-built for **Elite Auto Workshop** (Al Quoz, Dubai). 

This template includes a **Dynamic URL Personalization Engine** that allows you to pitch *any* auto workshop in Dubai with a customized version of the website in seconds—without editing any HTML or CSS files.

---

## 🚀 Key Features

* **Dynamic URL Personalization:** Instantly customize the garage name, phone, location, address, Google reviews count, and star rating on the fly just by appending search parameters to the URL (ideal for high-volume WhatsApp/Email cold outreach).
* **Premium Dark Automotive Aesthetic:** Styled with a sleek dark theme, energetic crimson red accents, glowing status indicators, and clean typography (**Outfit** and **Plus Jakarta Sans**).
* **Interactive Quote Estimator:** Client-side JavaScript widget that dynamically calculates starting service prices and durations based on vehicle make (Toyota, Nissan, BMW, etc.) and service type.
* **Direct WhatsApp Integration:** Establishes pre-filled booking messages that auto-fill details from the price estimator or the diagnostic booking form.
* **On-Site Proof Photo Grid:** Low-resolution workshop pictures are framed inside custom "Live Report" borders to preserve authenticity and prevent pixelation.
* **Google Maps Review Slider:** Responsive carousel displaying verified Google reviews (rating 5.0, 22 reviews) with review screenshots, reviewer details, and replies.
* **Mobile-First Layout:** Fixed floating CTAs (Call & WhatsApp) at the bottom of mobile screens for instant client conversion.

---

## 🔗 How to Use the Dynamic Personalization Links

You can host this site once (e.g., on GitHub Pages) and send customized links to different garages. The webpage will automatically update all headings, badges, phone numbers, contact forms, Google Maps statistics, and WhatsApp redirect links.

### Available URL Parameters:
- `name`: The garage name (URL-encoded).
- `phone`: The recipient's phone number (country code first, e.g. `971501234567`). If it starts with `0` (e.g. `0501234567`), it will be converted automatically.
- `phone_formatted`: How the phone number should display visually (e.g., `+971 50 123 4567`).
- `location`: The neighborhood/district of the garage (e.g., `Al Quoz`).
- `address`: The full garage address for the contact block.
- `rating`: Google star rating (e.g., `4.8`).
- `reviews`: Number of reviews on Google Maps (e.g., `57`).

### Example Personalization URLs:

1. **Default (Elite Auto Workshop - Al Quoz):**
   `https://yourusername.github.io/mechanics-website/`

2. **Personalized for "Salsabila Motors" in Al Quoz:**
   `https://yourusername.github.io/mechanics-website/?name=Salsabila%20Motors&phone=971505556789&phone_formatted=%2B971%2050%20555%206789&location=Al%20Quoz&address=Warehouse%2012%2C%20Al%20Quoz%20Industrial%20Area%203%2C%20Dubai&rating=4.9&reviews=45`

3. **Personalized for "Al Nahdha Auto Garage" in Deira:**
   `https://yourusername.github.io/mechanics-website/?name=Al%20Nahdha%20Auto%20Garage&phone=971549991234&phone_formatted=%2B971%2054%20999%201234&location=Deira&address=Opposite%20Auto%20Market%2C%20Deira%2C%20Dubai&rating=4.8&reviews=138`

---

## 🔧 File Structure & Manual Customization

* `index.html`: Core markup, price calculator, and dynamic parameter engine.
* `style.css`: Modern, responsive vanilla styling layout and animations.
* `brand given pics on google/`: Google Maps garage service photos.
* `cutomer review pics/`: Padded, legible customer review screenshots.

To modify the baseline pricing rules or multipliers, open the `<script>` tag inside `index.html` and edit the `priceTable` base prices or `brandModifications` multipliers.
