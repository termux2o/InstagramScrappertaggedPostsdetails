# Instagram Tagged Posts Scraper 📸

This project automates the process of scraping tagged post URLs from a specified Instagram profile using Selenium.

## 🚀 Features

- Automates Instagram login using your credentials
- Navigates to a user's tagged posts page
- Scrolls the page a custom number of times
- Extracts and stores post URLs
- Avoids duplicate entries by maintaining a CSV file

## 📋 Prerequisites

- Python 3.7 or higher
- Google Chrome installed
- A valid Instagram account

## 🧰 Installation

1. **Clone this repository** or download the notebook.

2. **Install required Python libraries**:
   ```bash
   pip install selenium webdriver-manager
Here’s how you can add the provided context to your `README.md` file in a clean, properly formatted way using Markdown syntax:
---
# 🧪 How to Run

**Launch the Jupyter Notebook:**

```bash
jupyter notebook
````

Open `taggedscript.ipynb`.

Run the notebook cells.

Enter the target username and scroll count when prompted:

* Instagram handle to fetch tagged posts from.
* Number of scrolls (higher number means more data but takes longer).

---

## 📝 Output

* Output is saved to a CSV file named `OUTPUT.csv`.
* Each line contains a unique post URL from the tagged section.

---

## ⚠️ Disclaimer

This script is for educational and personal use only.

Automated scraping of Instagram may violate its terms of service. Use responsibly.

