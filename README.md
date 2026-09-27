# .github

Defaults for the `ArvidDeJong` repositories.

- `.github/workflows/laravel-package.yml`: reusable CI for the `darvis/*` Laravel packages. Each package calls it from its own `tests.yml`; the PHP and Laravel matrix lives here.
- `CODE_OF_CONDUCT.md` and `.github/pull_request_template.md`: GitHub uses these for every repository that has no copy of its own.
- `.github/FUNDING.yml`: the Sponsor button, pointing to GitHub Sponsors. GitHub shows it on every repository without a funding file of its own, but only where **Sponsorships** is turned on under Settings → General → Features.

Dependabot does not fall back to this repository, so `.github/dependabot.yml` stays in each package.
