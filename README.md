
# CodeTantra Code Scraper

This project is a Python script that extracts code from a saved CodeTantra HTML page and writes it into a text file for easier access and use.

---

## Project Overview

- Parses the saved `test.html` (CodeTantra coding page HTML).
- Finds and extracts code from the editor area.
- Supports selecting different code tabs if multiple are present.
- Outputs all code lines neatly into a file called `out.txt`.


## 🛠Requirements

- Python 3.x
- BeautifulSoup4

Install dependencies with:

```bash
pip install beautifulsoup4
```

## How to Run

1. Save your CodeTantra code page as `test.html`.

2. Run the script:

```bash
python scraper.py
```
- By default, scrapes the first tab.

3. If you want to scrape a specific tab (e.g., 2nd tab):

```bash
python scraper.py 1
```
- (The script internally adds +1 to match CodeTantra's structure)

4. The extracted code will be saved in a file called `out.txt`.

## Output

- `out.txt` — contains the extracted code lines.

## Note

- Make sure test.html is in the same directory as scraper.py.

- This script only works with downloaded HTML files, not live websites.
