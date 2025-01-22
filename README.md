# Documentation as Code Bluenptint
This Documentation as Code repository has a blueprint to bootstrap the documentation as a code solution build using [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/).

### Examples
To review examples of the documentation projects built on the same technology stack please navigate to [Trusted By ...](https://github.com/squidfunk/mkdocs-material#trusted-by-) section of official documentation.

## FAQ

### How to run documentation site locally?
1. Clone or checkout this repository.
2. Create, and activate virtual environment: e.g. `python -m venv ../docs-env && source ../docs-env/bin/activate`. See https://docs.python.org/3/tutorial/venv.html for Python virtual environments documentation.
3. Install required Python dependencies - in the terminal, navigate to the cloned repository and run `pip install -r requirements.txt`.
4. Run `mkdocs serve` that will serve static documentation site on default 8000 port.

### How to contribute?
1. The `mkdocs.yml` file contains the navigation and configuration of the site.
2. The `docs/` folder contains the documentation content.
For more information, refer to [MkDocs](https://www.mkdocs.org/user-guide/writing-your-docs/) and [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) documentation.

### How to publish documentation site on GitHub?
[GitHub Actions](https://github.com/yevgen-ponomarenko/doc-as-code-blueprint/actions) is configured automatically to deploy the *main* branch to [GitHub Pages](https://github.com/yevgen-ponomarenko/doc-as-code-blueprint/settings/pages).

## Contact
Please feel free to reach out to Yevgen.Ponomarenko@gmail.com with any questions, suggestions, or feedback. You can use MS Teams or email communication channels.

## License
This repository is licensed with Apache.
