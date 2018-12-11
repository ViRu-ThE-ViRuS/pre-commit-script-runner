# pre-commit-script-runner

Auto-Run scripts using pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

### Using script-runner with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: https://github.com/ViRu-ThE-ViRuS/pre-commit-script-runner
        rev: ''  # Use the sha / tag you want to point at
        hooks:
        -   id: script-runner
            args: [''] # The bash scripts to run
