# How to use
## 1. コンテナを立ち上げる
```
docker compose up --build  -d
```
## 2. コンテナ内に入る
```
docker exec -it detected_heatmap bash
```

## 3. プログラムを実行
```
python detected_heatmap.py
```

## 4. 画像の確認
"detected_heatmap.py"と同じ階層に.png画像が生成される
