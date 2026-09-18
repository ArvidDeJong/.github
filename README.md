# .github

Defaults for the `ArvidDeJong` repositories.

- `.github/workflows/laravel-package.yml`: reusable CI for the `darvis/*` Laravel packages. Each package calls it from its own `tests.yml`; the PHP and Laravel matrix lives here.
- `CODE_OF_CONDUCT.md` and `.github/pull_request_template.md`: GitHub uses these for every repository that has no copy of its own.

Dependabot does not fall back to this repository, so `.github/dependabot.yml` stays in each package.
