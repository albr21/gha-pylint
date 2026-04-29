# gha-pylint

A GitHub Action to run pylint, analyzing your Python code for potential errors and style issues.
Working only on Linux based environment.

## Usage

```yaml
steps:
  - name: Run pylint
    uses: albr21/gha-pylint@1.0.0
    with:
      path: src
      lint-threshold: '7.0'
      pylintrc: .pylintrc
```

## Contributing

Check out the [CONTRIBUTING](CONTRIBUTING.md) file for guidelines on how to contribute to this project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
