# my-repo

## リポジトリsetup

- dependency botが自動作成した依存関係更新PRの自動マージのためにauto-merge設定有効化
  - 当該リポジトリの画面で下記設定
    - Settings => "Allow auto-merge"有効化
    - Settings => Actions => General => "Allow GitHub Actions to create and approve pull requests"有効化
  - なお直接ソースの動作に関わらないgithub action workflow関連の変更のみ自動マージしている
