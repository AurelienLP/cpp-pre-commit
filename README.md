# cpp-pre-commit

[pre-commit](https://pre-commit.com/)

## Installation

```bash
sudo apt update && apt-get install -y python3-pip
pip3 install pre-commit
pre-commit install
```

## Using the hooks

```yaml
-   repo: https://github.com/AurelienLP/cpp-pre-commit.git
    rev: master
    hooks:
    -   id: clang-format
```
