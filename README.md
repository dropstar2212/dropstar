# Dropstar Tools website

A responsive browser-based toolbox with:
- QR code generator (download PNG)
- Calculator
- Age calculator
- Unit converter (length, weight, temperature, volume and area)
- Image compressor (JPEG, WebP or PNG)
- PDF merger
- Password generator and locally encrypted password vault
- Word counter
- Text case converter
- Percentage and percentage-change calculator
- Discount calculator (INR)
- JSON formatter/minifier
- Color picker (HEX and RGB)
- Dropstar logo and favicon
- Support email: reachus@dropstar.co.in
- Support phone: 8884504563

## Run the website
1. Extract the ZIP file.
2. Open the extracted `dropstar_tools_website` folder.
3. Double-click `index.html` to open it in a modern browser.
4. If a browser blocks some local-file features, run a local web server:
   - Install Python if needed.
   - Open a terminal/Command Prompt in the project folder.
   - Run: `python -m http.server 8000`
   - Visit `http://localhost:8000`

## Important notes
- No app installation is needed for visitors. QR and PDF features load open-source libraries from CDNs and need internet access.
- Most tools process input locally in your browser.
- The password vault uses Web Crypto AES-GCM encryption with a key derived from the master passphrase and stores encrypted data in this browser's local storage. Use a strong unique passphrase. This starter vault is not a substitute for a professionally audited password manager.
- Keep your browser data safe if you need saved vault entries.
- Contact details appear in the support section near the bottom of the website and in the footer.
- Replace `assets/dropstar-logo.png`, `assets/favicon.png`, and `assets/favicon.ico` to use different branding.

## Files
- `index.html` — website structure
- `styles.css` — responsive styling
- `app.js` — tool functionality
- `assets/dropstar-logo.png` — logo
- `assets/favicon.png` and `assets/favicon.ico` — favicon files
