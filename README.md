# FeatureX220 Premium EV Scooter Website

Premium MG Windsor + NIU + Tesla inspired original website for FeatureX220. This is not an exact copy; it is a custom EV brand website.

## Pages included
1. `index.html` - Premium landing page with video hero
2. `models.html` - Model / variant page
3. `technology.html` - Smart technology page
4. `charging.html` - Fast charging page
5. `gallery.html` - Image and video gallery
6. `about.html` - Company / brand page
7. `contact.html` - Contact form + WhatsApp enquiry
8. `prebooking.html` - Pre-booking form
9. `dealer.html` - Become A Dealer page + dealer application form

## Fonts
Google Fonts used:
- Headings: Sora
- Body: Inter

## Change colours
Open `css/styles.css` and edit this section:

```css
:root{
  --primary:#2E7D32;
  --accent:#FFB703;
  --bg:#EEF7F2;
}
```

## Connect contact forms
Forms currently show a success message using JavaScript. To receive enquiries, connect one of these:

### Web3Forms example
Replace the form tag with:

```html
<form action="https://api.web3forms.com/submit" method="POST" class="form card">
  <input type="hidden" name="access_key" value="YOUR_ACCESS_KEY">
```

### WhatsApp
In `contact.html`, replace:

```html
91YOURNUMBER
```

with your WhatsApp number, for example `919876543210`.

## Replace images and video
Put your new files inside:
- `assets/images/`
- `assets/video/featurex220.mp4`

## Open website
Double click `index.html`, or upload the whole folder to hosting/cPanel/Netlify/Vercel.


## Current Theme
Option 3 Luxury EV theme applied: fresh light green background, deep green primary buttons, warm golden accent, and dark slate text.
