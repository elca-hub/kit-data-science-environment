# データサイエンス科目の環境をdockerでやってみよう

## サーバの立ち上げ方

```bash
docker compose up
```

## ライブラリのインストール方法

1. `requirements.txt`にインストールしたいライブラリを入力
2. `docker compose build`する
3. `docker compose up`で反映されているはず

## 参考元

[Jupyter Lab(Notebook)をローカル環境のDocker Composeで起動する方法
](https://dev.classmethod.jp/articles/jupyter-notebook-on-docker-compose/)

↑ ただし、`!date`をするとUTCになるので、このリポジトリでは日本時間にするように変更しています
