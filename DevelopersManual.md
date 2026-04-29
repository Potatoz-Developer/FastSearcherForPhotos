## Developer's Manual;

Want to use or modify FastSearcherForPhotos? Follow this quick guide:

###  Getting Started;

1. Download or clone the repository:

   ```bash
   git clone https://github.com/potatoz-developer/fastsearcherforphotos.git
   ```
2. Open the project folder
3. Run `index.html` in your browser

No installation required. it works instantly.

---

###  How to Customize;

You can easily edit the project:

* **Themes** → edit buttons inside `temaChips`
* **Styles** → edit `estiloChips`
* **Sources** → edit `fonteCards`
* **Search logic** → edit the JavaScript inside `<script>`

Example:

```js
const query = `${state.tema} ${state.estilo}`;
```

---

### Adding New Platforms;

To add a new search source:

1. Create a new card in HTML
2. Add a condition in JavaScript:

```js
if (state.fonte === "youtube") {
  url = `https://www.youtube.com/results?search_query=${encodeURIComponent(query)}`;
}
```

---

### ⚠️ Notes

* Always keep the file name as `index.html` for GitHub Pages
* If changes don’t appear, refresh the page
* To update results, press the search button again

---
###  Disclaimer

This project is provided for educational and creative purposes only.

The author does not encourage or support any illegal, harmful, or malicious use of this code. Any misuse of this project is the sole responsibility of the user.

By using this code, you agree to use it responsibly and in accordance with all applicable laws.
Requirements for Using This Code;
-Give proper credit to the original author (FastSearcherForPhotos by Potatoz Developer)
-Do not use this project for commercial purposes

---

## Contributing

Feel free to fork, improve, and share your version of this project.

Please make sure to:

* Give proper credit to the original author (FastSearcherForPhotos by Potatoz Developer)
* Do not use this project for commercial purposes

All contributions are welcome!


---

"Made with creativity, for all"
