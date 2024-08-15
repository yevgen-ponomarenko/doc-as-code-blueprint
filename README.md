# STOBG Project Performance Analytics Documentation Source
This Documentation as Code repository keeps the technical, end-user, and release documentation for CMiC Project Analytics.

## Built With
This site is build by using [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/).

### Examples
To review examples of the documentation projects built on the same technology stack please navigate to [Trusted By ...](https://github.com/squidfunk/mkdocs-material#trusted-by-) section of official 

## FAQ

### How to run documentation site locally?
1. Clone or checkout this repository.
2. Install Python and Pip using [these instructions for Python](https://realpython.com/installing-python/) and [these instructions for Pip](https://pip.pypa.io/en/stable/installation/).
3. In the terminal, navigate to the cloned repository and run `pip install -r requirements.txt` to install dependencies.
4. Then, run `mkdocs serve`, and open the http://127.0.0.1:8000/ site in your browser.

### How to run documentation site in Google Cloud Workstations?
> **_NOTE:_**  Python virtual environment has to be used for serving mkdocs site from Google Cloud Workspace.

> **_NOTE:_**  You can access HTTPS ports 80 and ports 1024 to 65535 on your workstations from your browser. See https://cloud.google.com/workstations/docs/use-port-forwarding for additional details

1. Clone or checkout this repository.
2. Create, and activate virtual environment: e.g. `python -m venv ../docs-env && source ../docs-env/bin/activate`. See https://docs.python.org/3/tutorial/venv.html for Python virtual environments documentation.
3. Install required Python dependencies - in the terminal, navigate to the cloned repository and run `pip install -r requirements.txt`.
4. Run `mkdocs serve` that will serve static documentation site on default 8000 port.
5. Your documentation site should be accessible at https://PORT-WORKSTATION-HOSTNAME in the browser, where PORT is the port number (default is 8000), and WORKSTATION-HOSTNAME is your workstation hostname. See https://cloud.google.com/workstations/docs/use-port-forwarding for additional details.

### How to contribute?
1. The `mkdocs.yml` file contains the navigation and configuration of the site.
2. The `docs/` folder contains the documentation content.
For more information, refer to [MkDocs](https://www.mkdocs.org/user-guide/writing-your-docs/) and [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) documentation.

### How to publish documentation site on GitHub?
[GitHub Actions](https://github.com/STOBG-Data-and-Analytics/cmic-project-analytics-docs/actions) is configured automatically to deploy the *main* branch to [GitHub Pages](https://github.com/STOBG-Data-and-Analytics/cmic-project-analytics-docs/settings/pages).

## Contact
Please feel free to reach out to Yevgen_Ponomarenko@epam.com with any questions, suggestions, or feedback. You can use MS Teams or email communication channels.

## License
This repository is licensed with STOBG.
