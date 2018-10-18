# New Repository Setup To-Do

- [ ] Add author name and email to `docs/_config.yml`
- [ ] Add basic information to `docs/index.md` about what the repo is for
- [ ] Activate the documentation site: **Settings** -> scroll to **Github Pages** -> source: **master branch /docs folder** and **Save**
- [ ] If applicable, edit the basic bug report template: `/.github/ISSUE_TEMPLATE/bug.md`
- [ ] If applicable, edit the basic pull request template: `/.github/PULL_REQUEST_TEMPLATE.md`
- [ ] If applicable, edit the contributing guidelines: `/.github/contributing.md`
- [ ] Add any necessary branch protection rules: **Settings** -> **Branches** -> **Branch Protection Rules**
  - [ ] Master branch must require:
    - [ ] Pull request reviews before merging
    - [ ] Dismiss stale pull request approvals when new commits are pushed
    - [ ] Require status checks to pass before merging
    - [ ] Require branches be up to date before merging
    - [ ] Include administrators