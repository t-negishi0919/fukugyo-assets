# fukugyo-assets

[fukugyo](https://github.com/t-negishi0919/fukugyo) パイプラインで使う Threads 投稿用サムネ画像の公開ホスティング先。

## 使い方

1. `images/` 配下に画像をドラッグ&ドロップでコミット（GitHub Web UI が一番楽）
2. その画像の raw URL をコピー
   - 形式: `https://raw.githubusercontent.com/t-negishi0919/fukugyo-assets/main/images/<filename>`
3. fukugyo リポの posts シートの `{account_name}_image_url` 列に貼る
4. 09/13/19 JST の post.py が IMAGE 投稿として送信する

## 命名

衝突回避のため、`{account_name}_{yyyymmdd}_{slot}.png` 形式を推奨。

例: `negi_ai_fukugyo_20260514_09.png`
