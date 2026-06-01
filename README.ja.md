# charcoal-cli リリース

`charcoal-cli` の公開リリースリポジトリです。

各リリースには、ビルド済みの Python パッケージ（`.tar.gz` ソース配布物と `.whl` ホイール）と、変更点を記載したチェンジログが含まれています。

## インストール

```bash
pip install https://github.com/charcoal-io/cli-releases/releases/download/v<VERSION>/charcoal_cli-<VERSION>-py3-none-any.whl
```

または、[リリースページ](https://github.com/charcoal-io/cli-releases/releases)からアーカイブをダウンロードして手動でインストールします。

```bash
pip install ./charcoal_cli-<VERSION>-py3-none-any.whl
```

## リリーススケジュール

リリースは、`charcoal-cli` リポジトリの `master` ブランチに変更がマージされると自動的に公開されます。
