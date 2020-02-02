# sample_docker_schemaspy
Docker Schemaspy コンテナの使用例です。

## 使い方
```bash
docker-compose up db
docker-compose up db -d
docker-compose up schemaspy
```

リストア等の DB コンテナ準備完了前に Schemaspy コンテナがドキュメントを生成しようとし、失敗する可能性があります。その際は、 DB コンテナの準備完了後に、再度上記コマンドで Schemaspy コンテナを実行してください。

## 参考ページ
- [docker-compose.yml に Schemaspy を利用するシンプルな service を書いて、データベースドキュメントを自動生成する – oki2a24](https://oki2a24.com/?p=12090)
- [schemaspy/schemaspy - Docker Hub](https://hub.docker.com/r/schemaspy/schemaspy)
- [Get Started — SchemaSpy 6.0.0 documentation](https://schemaspy.readthedocs.io/en/latest/started.html)
