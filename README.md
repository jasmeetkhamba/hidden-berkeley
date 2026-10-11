# Hidden Berkeley: HW2 starter

Create your own public website from this starter, then use a Jupyter notebook to edit the data it displays.

**Start here:** on the [HW2 template repository](https://github.com/macss-berkeley/hw2-hidden-berkeley-template), choose **Use this template → Create a new repository**. Name your copy `hidden-berkeley` and make it public. Clone your copy with GitHub Desktop and open its folder in VS Code. Follow [hw2_hidden_berkeley.ipynb](hw2_hidden_berkeley.ipynb).

## What is in this repository?

| File | What it does |
| --- | --- |
| `hw2_hidden_berkeley.ipynb` | Your instructions, data edits, and submission evidence. |
| `docs/_data/locations.csv` | The resource data. The notebook edits this file; the website reads it. |
| `docs/index.md` | The page heading, introduction, and supplied loop that displays the CSV rows. |
| `docs/_config.yml` and `docs/_layouts/default.html` | Supplied website settings and layout. |

GitHub Pages builds the website from `main` and `/docs`. After you push a changed CSV, GitHub rebuilds the page using the new data. Jupyter only edits and saves the data; it does not build the website. The `_data` folder name is required by the website builder.

## Purpose and sources

This website is for UC Berkeley students and visitors who want to learn about useful and interesting places around campus. The first eight resources were provided by COMPSCI 211A, and I added [Berkeley Art Studio](https://artstudio.berkeley.edu/) to highlight a fun place where people can take art classes. I used the official Berkeley Art Studio website to check who can register for classes.

## Website checks

My website: [Beyond the Classroom: Discover UC Berkeley](https://jasmeetkhamba.github.io/hidden-berkeley/)

I opened my website in a private browser window to make sure my changes appeared correctly. I checked that all nine resources were listed, including Berkeley Art Studio, and that the updated information for Morrison Library matched my CSV file. I also checked that the website showed my new heading and introduction, and that the official links for Morrison Library and Berkeley Art Studio opened the correct pages.