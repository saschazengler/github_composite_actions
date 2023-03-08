[![Lint codebase](https://github.com/saschazengler/github_composite_actions/actions/workflows/lint.yaml/badge.svg)](https://github.com/saschazengler/github_composite_actions/actions/workflows/lint.yaml)

# GitHub Composite Actions

Use these composite actions for avoiding redundant code in your workflow file.
You can reference the `action.yaml` files in your workflow like this:

```yaml
- name: Use npm composite action
  uses: saschazengler/github_composite_actions/npm@v1
```
