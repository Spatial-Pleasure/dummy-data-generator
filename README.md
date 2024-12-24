# Dummy-data-generator Readme

## ToDo :
- [ ] 環境構築を行う requirementsのエラー対応を行う。
- [ ] LMの定義を使用してデータを作成してみる
- [ ] 運用をまとめる

## setup

```bash
docker compose up -d

docker compose exec -it dummy-data-generator-db-1 psql -U postgres -d dummy_data_generator

```

## 概要はdocs/RD.mdを参照


