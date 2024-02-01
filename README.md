# flake8 pre-commit hook

pre-commit hook of flake8 with conda as a `language` / package manager.

For pre-commit: see [here](https://github.com/pre-commit/pre-commit)

For flake8: see [here](https://flake8.pycqa.org)

## Using flake8 with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/quantco/pre-commit-mirrors-flake8
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: flake8-conda
```
