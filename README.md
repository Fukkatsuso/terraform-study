# terraform-study

Terraformの勉強用リポジトリ

## Documents

- [インストール](https://learn.hashicorp.com/tutorials/terraform/install-cli)
- [GCPを用いたチュートリアル](https://learn.hashicorp.com/tutorials/terraform/google-cloud-platform-build)
- [GCP向けドキュメント](https://registry.terraform.io/providers/hashicorp/google/latest/docs)
  - [Getting Started with the Google Provider](https://registry.terraform.io/providers/hashicorp/google/latest/docs/guides/getting_started)
- [recommended practices](https://www.terraform.io/cloud-docs/guides/recommended-practices)

## Tips

- [apply時にvariablesをセットする](https://www.terraform.io/language/values/variables#variables-on-the-command-line)
  - [プレフィックス付き環境変数でもセット可能](https://www.terraform.io/language/values/variables#variables-on-the-command-line)
  - [設定の優先度](https://www.terraform.io/language/values/variables#variables-on-the-command-line)
- [GitHub Actionsで使うなら，tfstateファイルをGCSに置くなどの設定が必要](https://qiita.com/sand_bash/items/a3459c9a62d1c792ac2f)
  - [Terraform Cloudでも可](https://febc-yamamoto.hatenablog.jp/entry/2019/10/10/211831)

## TODO?

- [ ] tfenvを使う
- [ ] 新規開発時にTerraformを採用してみる
- [ ] 過去のプロジェクトをTerraformで管理する
