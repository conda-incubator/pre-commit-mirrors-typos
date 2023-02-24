ruff(-conda) mirror
====================

Mirror of ruff for pre-commit with conda as a language.

For pre-commit: see https://github.com/pre-commit/pre-commit
For ruff: see https://github.com/charliermarsh/ruff

### Using ruff with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/Quantco/pre-commit-mirrors-ruff
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: ruff-conda
```

