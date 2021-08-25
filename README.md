# ClangFormat hook for pre-commit

[ClangFormat](http://clang.llvm.org/docs/ClangFormat.html) package for [pre-commit](http://pre-commit.com).

## Using clang-format with pre-commit

```yaml
-   repo: https://github.com/alanpapalia/pre-commit-clang-format
    rev: fefc91d9742bbe2898799b6c31f25c792fc8093a
    hooks:
    -   id: clang-format-12
```
