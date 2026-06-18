# Sample CI/CD Testing Repo

A minimal Node.js example demonstrating a Jest-based test suite with a GitHub Actions CI workflow.

Features
- Calculator example at `src/calculator.js`.
- Unit tests at `tests/calculator.test.js` using Jest.
- CI workflow located at `.github/workflows/ci.yml` (runs on push and PR).

Prerequisites
- Node.js (recommended 20.x)
- npm (bundled with Node.js)

Quick start

```bash
npm install
npm test
```

Available scripts
- `npm test` — run the Jest test suite
- `npm run test:watch` — run tests in watch mode

CI behavior

The GitHub Actions workflow runs on pushes and pull requests to `main` and `master`, installs dependencies with `npm ci`, and runs the Jest tests in CI mode.

Contributing
- Open a PR with a clear description and tests for any changes.

License
- MIT