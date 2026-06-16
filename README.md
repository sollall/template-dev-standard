# template-dev-standard

## Setup

```sh
uv sync
git config core.hooksPath .githooks
```

`git push` 時に `.githooks/pre-push` が実行され、`ruff check` / `ruff format --check` が走ります。
