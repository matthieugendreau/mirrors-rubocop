mirrors-rubocop
===============

Mirror of rubocop gem for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit
For rubocop: see https://github.com/bbatsov/rubocop


### Using rubocop with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: git://github.com/pricematch/mirrors-rubocop
        sha: ''  # Use the sha you want to point at
        hooks:
        -   id: rubocop
