# Web-Scrapping

A small Jupyter notebook that scrapes the list of foreign university partnerships (MoUs) from the [IIT Madras Global Engagement page](https://ge.iitm.ac.in/mou/foreign-universities) using `requests` and `BeautifulSoup`.

## What's inside

| File | Description |
|------|-------------|
| `scrapping.ipynb` | Fetches the page, parses the HTML and extracts the data |
| `datasorted.xlsx` | The sorted data collected from the page |

## Tech stack

- Python 3
- `requests` for HTTP
- `BeautifulSoup` (`bs4`) for HTML parsing
- Jupyter Notebook

## Run it

```bash
pip install requests beautifulsoup4 jupyter
jupyter notebook scrapping.ipynb
```

Run the cells in order. The notebook downloads the page live, so it needs an internet connection and may need updating if the site layout changes.

## Note

The target page is rendered by a JavaScript framework (Next.js). If a plain `requests` call returns incomplete data, a headless browser such as Selenium or Playwright is the next step.


---

<sub>Made by [tanaytejush](https://github.com/tanaytejush)</sub>
