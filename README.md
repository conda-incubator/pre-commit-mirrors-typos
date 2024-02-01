# typos pre-commit hook

pre-commit hook of typos with conda as a `language` / package manager.

For pre-commit: see [here](https://github.com/pre-commit/pre-commit)

For typos: see [here](https://github.com/crate-ci/typos)

## Using typos with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/quantco/pre-commit-mirrors-typos
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: typos-conda
```
