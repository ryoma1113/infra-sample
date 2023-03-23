###### 変更ファイル以下
- package.json
    - --hide-modulesを消す
- .env
    - コピーして、MAILオプション、AWSオプションを変更する
- docker-compose.yml
    - 必要であれば、port番号を変更`WEB_PORT:-81` `DB_PORT:-3316`等　※　localhost:81などでアクセスするようになる。
    - `project-name`部分をプロジェクト名に変更
