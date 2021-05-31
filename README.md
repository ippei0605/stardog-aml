# stardog-aml
Stardogの勉強です。

## Finding Fraud with Stardog
https://www.stardog.com/blog/finding-fraud-with-stardog/

* データをダウンロードする。
  - https://github.com/stardog-union/stardog-examples/tree/develop/examples/aml

* データを配置する。
  - $STARDOG_HOME/aml 

* Stardog を起動する。
    ```
    % stardog-admin server start
    ```

* データをロードする。
    ```
    % ./create_db.sh
  
    (...省略...)
  
    Transaction committed successfully in 00:00:00.404  <-- このメッセージで完了
    ```
  
* Stardog Studio で確認する。
    - fraud_demo が作成されている。