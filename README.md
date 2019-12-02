flake8(-conda) mirror
====================

Mirror of flake8 for pre-commit with conda as a language.

For pre-commit: see https://github.com/pre-commit/pre-commit
For flake8: http://flake8.pycqa.org/

### Using black with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/Quantco/pre-commit-mirrors-flake8
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: flake8-conda
```

