## Strato Setup

- In strato an internal redirect to the folder `public` has been created
- index.html rests in this directory

## Github Workflow

- Workflow `prodDeploy.yml` has been created within directory `.github/workflows`
- This utilizes a script from github
- Script pushes entire repository content to designated server location
- Server location is specified in `prodDeploy.yml`
- Script is triggered for every `push` on `master`

## Dependencies

### Bootstrap

- Sekhmet Theme uses `Bootstrap`
- Bootstrap is downloaded and copied into directory `themes/sekhmetTheme/static/`
- Connecting html script-tag rests in `footer.html`

### Jquery

- Sekhmet Theme uses `Jquery`
- Inclusion analogue to `Bootstrap`
