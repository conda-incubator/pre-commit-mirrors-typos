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

### Some Useful Exceptions
For the exact documentation on how to ignore certain typos, see: https://github.com/crate-ci/typos#false-positives

In our projects, some shorter German works are too similar to English words and are picked up. Here is a list of commonly encountered typos:

```toml
[default.extend-words]
als = "als"
alle = "alle"
autor = "autor"
beginn = "beginn"
ende = "ende"
iif = "iif"
ist = "ist"
feld = "feld"
tage = "tage"
titel = "titel"
```

### Flagging Unrecognized Typos
If you notice that there is a typo in your project that is not being caught by `typos`, simply open an issue in this repository.
