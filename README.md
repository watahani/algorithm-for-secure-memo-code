# README

暗号技術のすべてのサンプルコード

## セットアップ

Python と .Net Core のインストール

### Python

Python 3.7 をダウンロード & インストール

https://www.python.org/downloads/

### .Net Core

Download .Net Core SDK からダウンロード & インストール

https://dotnet.microsoft.com/download


### 以下のコマンドを打つ

dotnet interactive のインストール

```ps1
dotnet tool install --global Microsoft.dotnet-interactive
```

jupyter notebook のインストール

```ps1
pip install pipenv
pipenv install
```

C# ランタイムのインストール

```ps1
pipenv shell
dotnet interactive jupyter install
```

起動

```ps1
pipenv run jupyterlab
```

