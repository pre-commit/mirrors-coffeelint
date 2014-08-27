coffeelint mirror
================

Mirror of coffeelint package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For coffeelint: see https://github.com/clutchski/coffeelint


### Using coffeelint with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: git://github.com/pre-commit/mirrors-coffeelint
        sha: ''  # Use the sha you want to point at
        hooks:
        -   id: coffeelint
