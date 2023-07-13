# tech-thurs

# パワーシェルがおすすめ

ssh ec2-user@オープンアドレス -i 鍵のパス
例: ssh ec2-user@ec2-34-238-43-171.compute-1.amazonaws.com -i "C:\Users\student\Desktop\木システム開発\key.pem"

# docker compose
docker compose up 起動
Ctrl + C 終了

# Mysql
docker compose exec 対象コンテナ名 コンテナ内で実行したいコマンド
今のコンテナ名は mysql

クライアントの起動は↓
mysql 接続するデータベース名

docker compose exec mysql mysql データベース

# webに接続
http://EC2インスタンスのIPアドレス(パブリックIPv4)/ファイル名




