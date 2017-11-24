# 11:00-

- Service 業務ロジック  
    - Controllerから呼び出される  

- Dao SQL実行  
    - SQLの結果をEntityにデータ格納
    - Entity 業務データ  

- Spring  
    - Webアプリと Java標準のAPIの間に入る
    - 面倒で冗長な部分をSpringがやってくれる
    - 認証、認可、キャッシュ、トレース

- DIコンテナで管理されているものは、Beanと呼ばれる  
    - Controller, Service, Dao
