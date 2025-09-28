# Direct Download Search 🔍

## Enhanced File Discovery Tool

**Disclaimer:** This tool is for educational purposes and responsible use. Please respect copyright laws and do not use this tool to obtain copyrighted material.

### What Is It?

**Direct Download Search** is a modern, responsive web application that helps users find direct download links for files across the internet. The tool leverages advanced search operators to locate publicly accessible files on open web directories while filtering out potentially harmful or unwanted sources.

This enhanced version features a sleek, modern interface with improved usability and expanded search capabilities across multiple search engines.

---

### Features ✨

* **Modern Interface:** Clean, responsive design with gradient backgrounds and smooth animations.
* **Multiple Search Engines:** Search across Google, Startpage, and FilePursuit.
* **Smart File Filtering:** Pre-configured filters for movies, music, books, software, mobile apps, and images.
* **Optimized Queries:** Automatically constructs advanced search queries with exclusion filters.
* **Mobile Responsive:** Works seamlessly on desktop, tablet, and mobile devices.
* **Real-time Feedback:** Dynamic placeholders and visual feedback based on selected categories.

---

### File Categories

* **All Files:** General search across all file types.
* **Movies/TV:** Video files (`mkv`, `mp4`, `avi`, `mov`, `mpg`, `wmv`, `divx`, `mpeg`).
* **Music:** Audio files (`mp3`, `wav`, `ac3`, `ogg`, `flac`, `wma`, `m4a`, `aac`).
* **Books:** Document formats (`MOBI`, `CBZ`, `CBR`, `EPUB`, `PDF`, `DOC`, `DOCX`).
* **Software:** Executables and archives (`exe`, `iso`, `dmg`, `tar`, `7z`, `rar`, `zip`, `apk`).
* **Mobile Apps:** Mobile applications (`apk`, `ipa`).
* **Images:** Picture formats (`jpg`, `png`, `gif`, `bmp`, `tiff`, `psd`).

---

### Search Engines

* **Google:** Uses advanced operators to find open directories.
* **Startpage:** Privacy-focused Google results.
* **FilePursuit:** Specialized file search engine with sorting by date.

---

### How to Use

1.  **Select File Type:** Choose from the category buttons (All Files, Movies/TV, Music, etc.).
2.  **Choose Search Engine:** Pick between Google, Startpage, or FilePursuit.
3.  **Enter Search Term:** Type your query in the search box (dynamic placeholder provides examples).
4.  **Search:** Click the search button or press Enter to open results in a new tab.

---

### Technical Details

#### Built With

* `HTML5` with semantic markup
* `Bootstrap 5` for responsive design
* `Font Awesome 6` for icons
* `Vanilla JavaScript` for functionality
* `CSS3` with modern features (gradients, backdrop-filter, transforms)

#### Search Query Construction

The tool automatically constructs optimized search queries:

* Adds file type filters based on selected category.
* Excludes common malicious domains and unwanted file types.
* Uses `intitle:index.of` to target open directories.
* Filters out dynamic pages (`jsp`, `php`, `html`, etc.).

#### FilePursuit Integration

Special handling for FilePursuit searches:
`https://filepursuit.com/pursuit?q={query}&type={category}&sort=datedesc`

---

### Installation & Usage

This is a single HTML file that runs entirely in the browser:

1.  Download the `HTML` file.
2.  Open it in any modern web browser.
3.  Start searching immediately - no installation required.

---

### Browser Compatibility

* Chrome/Chromium 88+
* Firefox 85+
* Safari 14+
* Edge 88+

---

### Security Features

* Opens search results in new tabs with `noopener`, `noreferrer` for security.
* Proper URL encoding to prevent injection attacks.
* No external dependencies beyond `CDN` resources.
* No data collection or tracking.

---

### Contributing

Contributions are welcome! Please feel free to:

* Report bugs or suggest improvements via GitHub Issues.
* Submit pull requests for new features or fixes.
* Suggest new search engines or file categories.
* Improve documentation.

---

### Development

The project uses modern web standards and requires no build process. Simply edit the `HTML` file and refresh the browser to see changes.

---

### License

This project is open source and available under the **MIT License**.

**Note:** This tool helps locate publicly accessible files on open web directories. Users are responsible for ensuring they comply with applicable laws and respect intellectual property rights when downloading content.
