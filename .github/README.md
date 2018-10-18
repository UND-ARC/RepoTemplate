# New Repository Setup To-Do

## Repository Settings

- [ ] Add author name and email to `/docs/_config.yml`
- [ ] Activate the documentation site: **Settings** -> scroll to **Github Pages** -> source: **master branch /docs folder** and **Save**
- [ ] Enable vulnerability alerts: **Settings** -> scroll to **Data Services** -> check **Vulnerability Alerts**
- [ ] Add any necessary branch protection rules: **Settings** -> **Branches** -> **Branch Protection Rules**
  - [ ] Master branch must require:
    - [ ] Pull request reviews before merging
    - [ ] Dismiss stale pull request approvals when new commits are pushed
    - [ ] Require status checks to pass before merging
    - [ ] Require branches be up to date before merging
    - [ ] Include administrators

## Metadata

- [ ] Add basic information to `/docs/index.md` about what the repo is for
- [ ] Add basic information to this file `/.github/README.md` about what the repo is for (should be similar to `/docs/index.md`)
- [ ] If applicable, edit the basic bug report template: `/.github/ISSUE_TEMPLATE/bug.md`
- [ ] If applicable, edit the basic pull request template: `/.github/PULL_REQUEST_TEMPLATE.md`
- [ ] If applicable, edit the contributing guidelines: `/.github/contributing.md`
