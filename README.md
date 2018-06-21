coffeelint mirror
================

Mirror of coffeelint package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For coffeelint: see https://github.com/clutchski/coffeelint


### Using coffeelint with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: https://github.com/pre-commit/mirrors-coffeelint
        rev: ''  # Use the sha / tag you want to point at
        hooks:
        -   id: coffeelint
