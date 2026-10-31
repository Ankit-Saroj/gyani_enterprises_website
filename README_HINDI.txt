# GYANI ENTERPRISES Website

A responsive, editable business website built with plain HTML, CSS and JavaScript. No build tools or paid hosting are required to preview it.

## Included business details
- Business: GYANI ENTERPRISES
- Proprietress: Mrs. Gyani Devi
- Experience: approximately 15–20 years (as provided)
- Services: 100–1000 feet borewell drilling, handpump installation/repair, submersible installation/repair, compressor flushing / borewell cleaning
- Equipment: small and large drilling machines, compressor machines
- Phone: +91 93365 23775
- Address: Madarpur, Jamalpur, Jaunpur, Uttar Pradesh – 222105
- GST: 09CZJPD5595D1Z4

## Run in VS Code (Windows 10)
1. Extract `GYANI_ENTERPRISES_WEBSITE.zip`.
2. Open VS Code.
3. Select **File → Open Folder** and open the extracted `gyani_enterprises_website` folder.
4. Open `index.html`.
5. For easiest preview, install the **Live Server** extension in VS Code.
6. Right-click `index.html` → **Open with Live Server**.
7. The website opens in your browser. Save edits and the page refreshes automatically.

You can also double-click `index.html` to open it without Live Server.

## Customize your website
- **Business name, services, address, GST, phone:** edit `index.html`.
- **Colours, fonts, spacing, layout:** edit `styles.css`.
- **WhatsApp form and mobile menu:** edit `script.js`.
- **Business board image:** `assets/business-board.png`.
- **Logo:** the current `GE` logo is made with HTML/CSS. Search for `brand-mark` in `index.html` and `styles.css` to change it. To use your own logo image, replace the `GE` span with an `<img>` tag and style it in `styles.css`.
- **Photos:** the hero and about photos use Unsplash; the work gallery uses Wikimedia Commons images with visible source and license credits. Replace image URLs in `index.html` and the hero background URL in `styles.css` with your own image paths, for example `assets/drilling-machine.jpg`. Put your photos inside the `assets` folder.

## Important notes
- The enquiry form opens WhatsApp with the visitor's entered details. It does not save enquiries to a database or send them to an email server.
- The phone and WhatsApp buttons use +91 93365 23775. Update both links if the number changes.
- Online photos currently use Unsplash and Wikimedia Commons image URLs and need an internet connection. Replace them with your own local images for an offline website. Keep the gallery image credits if you continue using the current Wikimedia Commons photos.
- This is a frontend business website. It does not include an admin dashboard or database.
- Before publishing, verify the business details, GST number, service area, and claims. The 15–20 years experience statement is based on the information supplied.
