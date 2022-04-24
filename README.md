### 環境構築
```
python -m venv venv
.\venv\Scripts\activate

pip install --upgrade pip
pip install -r requirements.txt
```

### 実行
```
python opencv_draw_binarize.py
```

### 操作方法
<pre>
あらかじめwebcamなどを接続しておく

ファイルを実行すると画面が自動的に立ち上がる
1. 画面をスクショする
    t でwebcamのフレーム画像をスクショする
    スクショした後に表示された画面(右？)で基本的に作業を行う
2. 基準となる実寸法を決める
    マウスをドラッグして引かれる線を定規などにあてがう
    c を押すと寸法入力画面が開く
    デフォルト設定では引いた線分の長さが 10 mm になる
    適当に設定して 適用 ボタンを押す
3. 画面のリセット
    再度 t を押し、画面をクリアする
4. マウスをドラッグし、寸法を描画していく
5. 保存する
    s を押しスクショ画面を保存する
    data フォルダにスクショ画像が保存される
</pre>