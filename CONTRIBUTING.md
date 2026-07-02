# Contributing to Technical Arts MTY

Thanks for your interest in contributing. This guide applies across the
organization's repositories. By participating, you agree to our
[Code of Conduct](CODE_OF_CONDUCT.md).

## Getting started

The shared entry point is the notes repository, which holds the projects and
contribution guides:

```
gh repo clone Technical-Arts-MTY/notas     # first time only
cd notas
python notes.py
```

New contributors are welcome to join the **Open Source** WhatsApp community and
the biweekly development meeting (see the organization profile).

## Ways to contribute

- Fix bugs or implement features from the issue tracker.
- Improve documentation, examples, and guides.
- Report reproducible issues with clear steps.
- Propose new work under an existing engineering area.

## Workflow

1. **Find or open an issue.** Discuss the change before large work; look for
   `good first issue` labels to get started.
2. **Branch.** Create a topic branch from `main`
   (e.g. `fix/sensor-timeout`, `feat/rothc-solver`).
3. **Make focused changes.** Keep pull requests small and self-contained.
4. **Document and test.** Update the `README`/docs and add tests where it
   applies. Measurements should state units, uncertainty, and method.
5. **Open a pull request.** Describe *what* changed and *why*, and link the
   related issue.
6. **Review.** A maintainer will review; discussion happens on the PR. Address
   feedback by pushing follow-up commits.

## Commit and PR guidelines

- Write clear, imperative commit messages (e.g. `Add RothC time-step guard`).
- One logical change per pull request.
- Keep formatting and style consistent with the surrounding code.

## Licensing

Unless a repository states otherwise, contributions are accepted under the
[MIT License](LICENSE). By submitting a contribution, you agree that it may be
distributed under those terms.

## Questions

Open a [discussion](https://github.com/orgs/Technical-Arts-MTY/discussions) or
reach out through the communities listed in the organization profile.
