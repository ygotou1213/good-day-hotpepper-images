# ③サブビジュアル 参考画像ライブラリ

③サブビジュアルは①のような固定パターンローテーションを持たず、月ごとにユーザーとの議論で部位・
技法・雰囲気を決める運用（`hotpepper-image-cycle-design.md`「③サブビジュアルの内容のみユーザーとの
議論で決める」参照）。このフォルダは、その議論の材料としてユーザーが共有した構図・技法の参考画像を
ストックする場所。①のポーズ参考画像（`_reference/pose-references/`）と同様、**人物本人ではなく
構図・技法・雰囲気のみを参考にする**。

## 現在の登録画像

| ファイル | 内容 |
|---|---|
| `subvisual-01-mug-marble-pearl-nail.png` | 手でマグカップを持つ構図。ネイルは微粒子パール／マーブル質感の「ちゅるん」ツヤ系、5指で色・柄違い（無地パール2色＋マーブル2色）。左に5色のカラースウォッチ（ピンクパール・シルベージュパール・ローズパール・クリームパール・ラベンダーグレーパール）（2026-07-27ユーザー共有） |
| `subvisual-02-knit-mug-torso-orange-unsplash.jpg` | オレンジのローゲージニットの女性が胸元で両手でマグを持つ実写。首元〜腰のフレーミング、無地のくすんだ背景、小物なし。AI感を抑える構図・光・質感の参考（Unsplash https://unsplash.com/photos/fdR0mlAvHKI 、2026-10-31 Claude取得。マグのロゴは流用しない） |
| `subvisual-03-knit-mug-torso-red-unsplash.jpg` | 赤いニットの女性が両手でマグを持つ実写。同上の参考（Unsplash https://unsplash.com/photos/hMw1-dxitxk 、2026-10-31 Claude取得） |
| `subvisual-04-side-light-black-mug-unsplash.jpg` | ニットの女性が胸の高さで両手で黒いマグを包む実写。片側（右）からの窓光で左側が暗く沈む陰影、手元にピントを置いた浅い被写界深度、くすんだティール〜グレーの低彩度トーン。芸術性を上げる光と陰影の参考（Unsplash https://unsplash.com/photos/H77F2WMUXUQ 、顔はモザイク処理済み、2026-10-31 ユーザー指定・Claude取得） |
| `subvisual-05-slender-hands-knit-mug-unsplash.jpg` | ニットの女性が両手でマグを持つ実写。指が細く指先へ向かって細くなる、小指が明らかに細い、指ごとに曲がり方・爪の角度が違う、美しい手の形の手本（Unsplash https://unsplash.com/photos/G8pMDFlHhwk 、2026-10-31 Claude取得。爪は短めなので長さは流用しない） |
| `subvisual-06-slender-hands-pink-mug-unsplash.jpg` | 片手を持ち手に、もう片手を底に添えてマグを持つ実写。細く長い指・指先の細さの手本（Unsplash https://unsplash.com/photos/UBvV5TgxzjE 、同上） |

## 新しい参考画像を追加する手順

1. このフォルダに画像を保存し、わかりやすいファイル名にリネーム（subvisual-連番-内容slug.png）
2. 上記の表に1行追記
3. 次回③の方向性を議論する際にこのフォルダを確認する
4. git commit・push
