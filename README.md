# terraform練習用リポジトリ

AWSインフラをterraformを使って構築する

# インストール

公式サイトを参考にインストールすること

https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli

# 初期化

rfファイルがあるファイル階層に移動

```
terraform init
```

# 実行

```
terraform apply
```

# 削除

```
terraform destroy
```

# 検証

ファイルを変更した際、以下のコマンドで差分を検出できる

```
terraform fmt
```

tfファイルの構文チェック

```
terraform validate
```