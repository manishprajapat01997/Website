# खेताराम बलारा — सरपंच प्रत्याशी, मौलासर (वेबसाइट)

Static हिंदी वेबसाइट (HTML + CSS)। GitHub Pages पर सीधे चलती है।

## GitHub पर लाइव करने के स्टेप
1. github.com पर नया repository बनाएँ (जैसे `maulasar-sarpanch`) — Public रखें।
2. इस फोल्डर की सभी फाइलें (`index.html`, `style.css`, `images/`, `.nojekyll`) upload करें (Add file → Upload files)।
3. Repository → **Settings → Pages** → Source: **Deploy from a branch** → Branch: `main` / `(root)` → **Save**।
4. 1–2 मिनट बाद लिंक मिलेगा: `https://<आपका-username>.github.io/maulasar-sarpanch/`

## बाद में अपडेट कैसे करें
- **टेक्स्ट बदलना**: GitHub में `index.html` खोलें → ✏️ Edit → बदलाव → Commit।
- **नई फोटो जोड़ना**: `images/` फोल्डर में फोटो upload करें, फिर `index.html` में
  `<img src="images/नाम.jpg" alt="विवरण">` लगाएँ (गैलरी में `<div class="gallery">` के अंदर)।
- **रंग बदलना**: `style.css` में सबसे ऊपर `:root` के रंग।
