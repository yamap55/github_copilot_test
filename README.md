# github copilot test

本リポジトリは GitHub Copilot を試すためのリポジトリです。
[GitHub Copilot](https://copilot.github.com/) に登録後にお使いください。

## 内容

- [devcontainer](https://code.visualstudio.com/docs/remote/containers)
- lint
  - [flake8](https://flake8.pycqa.org/en/latest/)
  - [black](https://black.readthedocs.io/en/stable/)
  - [Pylance](https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance), [pyright](https://github.com/microsoft/pyright)
  - [hadolint](https://github.com/hadolint/hadolint)
- [pytest](https://docs.pytest.org/en/stable/)
- [poetry](https://python-poetry.org/)
- [GitHub Actions](https://github.co.jp/features/actions)
- [logging](https://docs.python.org/ja/3/howto/logging.html)

## 環境詳細

- Python : 3.9

### 利用手順

1. VS Code 起動
2. 左下の緑色のアイコンクリック
3. 「Remote-Containersa: Reopen in Container」クリック
4. しばらく待つ
   - 初回の場合コンテナー image の取得や作成が行われる
5. 起動したら開発可能
6. `fizzbuzz.pu` や `file_util.py` を開く
7. 適当に `class` や `def` などと打ってみる
8. 補完される
