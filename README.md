typos(-conda) mirror
====================

Mirror of typos for pre-commit with conda as a language.

For pre-commit: see https://github.com/pre-commit/pre-commit
For typos: see https://github.com/crate-ci/typos

### Using typos with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/Quantco/pre-commit-mirrors-typos
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: typos-conda
```

