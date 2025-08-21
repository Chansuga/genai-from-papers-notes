# 第2章 入力データの特徴量化

## 環境構築の前提条件

このフォルダ内プログラムを実行するには、以下の準備が必要です：

- Python 3.12 以上
- VSCode
- VSCodeのMulti-root Workspaces機能を使用し、ワークスペースとして開いている（やり方は[こちら](../README.md)を参照）

また、Python の依存関係は `pyproject.toml` に記載されています。

## 環境構築

### 1. chapter2のワークスペースを開く
chapter2 ディレクトリに仮想環境を作成します。
VSCode の ターミナルの追加で`chapter2` を選択します。

### 2. uvのインストール

依存関係の解決には`uv`を利用します。
`uv`を使ったことがない場合、以下の方法でインストールしてください。

`pip`を使う場合：
```bash
pip install uv
```

MacまたはLinuxの場合：
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

### 3. Python 仮想環境の作成と依存関係のインストール

依存関係のインストール
```bash
uv sync
```

インストール後に作成した仮想環境をアクティブにします。

```bash
source .venv/bin/activate
```

## 画像の出典とライセンスについて

`image/` ディレクトリ内の画像（論文スクリーンショット）は、以下の論文より引用しています。

- 論文タイトル: Toward a Theory of Tokenization in LLMs
- 著者: Jacob Andreas, et al.
- arXiv: [2404.08335](https://arxiv.org/abs/2404.08335)
- ライセンス: [CC BY 4.0 (Attribution 4.0 International)](https://creativecommons.org/licenses/by/4.0/)

これらの画像はCC BY 4.0ライセンスの下で利用しています。著作権は著者に帰属します。
