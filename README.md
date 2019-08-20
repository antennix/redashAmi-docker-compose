## redashAmi-docker-compose

Redash by AmazonMachineImageで、localhostのmysqlを参照するようにする

https://redash.io/help/open-source/setup#aws

### 動作環境
下記AMIで動作確認済
```ap-northeast-1	ami-0c7d9b740e997aa69```

### Setup
- 起動したインスタンスの/opt/redash配下のdocker-compose.ymlを上書き
- `docker-compose up -d`
- Redashコンソールからmysql接続設定を行う
