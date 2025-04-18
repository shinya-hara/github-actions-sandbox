# github-actions-sandbox

## 試したもの

- Environment を活用したデプロイ CI
  - https://docs.github.com/ja/actions/deployment/targeting-different-environments/using-environments-for-deployment
- SFTP でのデプロイ
  - [.github/workflows/sftp.yml](.github/workflows/sftp.yml)
- リポジトリ内の別ファイルを読み込んでアクションで利用する（AI 向けのプロンプトを markdown で記述している場合などを想定）
  - [.github/workflows/read-file.yml](.github/workflows/read-file.yml)
