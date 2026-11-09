# DAISY documentation

The site is built with MkDocs. Install its dependencies with
`python -m pip install -r requirements.txt` and preview it with
`python -m mkdocs serve`.

The GitHub Actions workflow builds and deploys the site when changes are pushed
to `main`, including merged pull requests. It can also be run manually. In the
repository's **Settings → Pages**, set the build and deployment source to
**GitHub Actions**.
