# infra

1. `terraform.tfvars` ファイルの準備

    以下のファイルを作成。
    プロジェクト名、環境名、ユーザー名、パスワードはそれぞれ任意の値を設定。

    `/10_infra/terraform.tfvars`

        project     = "{プロジェクト名}"
        environment = "{環境名}"
        username    = "{管理ユーザー名}"
        password    = "{管理パスワード}"

    (*) 管理ユーザー名、管理パスワードは DB のアクセスで利用

# Required secrets

|Name|Value|
|---|---|
| `SLACK_WEBHOOK_URL` | Slack Incomming Webhook URL |
| `AWS_IAM_ROLE_ARN`  | AWS IAM Role ARN |

