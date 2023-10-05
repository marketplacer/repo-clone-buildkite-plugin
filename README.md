# Git Clone Buildkite Plugin
Plugin for buildkite to perform a simple git clone of an extra repository at post-checkout.

# Example
```
- label: Some command
    plugins:
      - marketplacer/repo-clone:
          repository: git@github.com:marketplacer/repo-clone-buildkite-plugin.git
```
