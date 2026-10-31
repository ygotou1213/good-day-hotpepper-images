# キービジュアル・ポーズ参考画像ライブラリ

①キービジュアルのポーズ・アングルローテーション用の参考画像を格納する。**人物（モデル本人）は
参考にせず、ポーズ・構図・アングルのみをAI生成の参考にする**（`hotpepper-image-cycle-design.md`
「人物（AIキャラクター）の一貫性方針」参照。顔・肌・髪等は確定リファレンスセット（同一AI
キャラクター）を優先する）。

## 現在の登録パターン

| ファイル | 内容 | 対応パターン# |
|---|---|---|
| `pose-06-both-hands-up-tilted-back.png` | 両手を頭上（髪）に添え、顔を仰け反らせて目を閉じるポーズ（2026-07-27ユーザー共有） | 6 |
| `pose-07-buttoning-coat-looking-down-unsplash.jpg` | 胸の前でコートのボタンを両手で留める、伏し目（Unsplash https://unsplash.com/photos/66gf8UpnVh8 、2026-10-31 Claude取得） | 7 |
| `pose-08-holding-coat-front-chest-unsplash.jpg` | 両手でコートの前身頃を胸の中央で合わせる、カメラ目線（Unsplash https://unsplash.com/photos/rDxga5YbQVQ 、同上） | 8 |
| `pose-09-seated-hands-on-table-unsplash.jpg` | テーブルに座り両腕を置いて手を前で重ねる（Unsplash https://unsplash.com/photos/LFGF6SL3Co0 、同上） | 9 |
| `pose-10-look-back-over-shoulder-unsplash.jpg` | 歩きながら肩越しに振り返る、髪とコートが動く（Unsplash https://unsplash.com/photos/2MeR7oeudlE 、顔はモザイク処理済み、2026-10-31 Claude取得） | 10 |
| `pose-11-walking-in-wind-unsplash.jpg` | 風の中を大股で歩く横〜斜め後ろのアングル（Unsplash https://unsplash.com/photos/vzfk2QjP4l0 、同上） | 11 |
| `pose-12-crouching-arms-on-knee-unsplash.jpg` | しゃがんで膝の上で腕を重ね、低めのアングルから見据える（Unsplash https://unsplash.com/photos/IDC7g-ccgv0 、同上） | 12 |

**ポーズ参考の使い方（2026-10-31）**：実在人物の写真は、顔をモザイク処理してから添付する（顔立ちが生成画像に混ざるのを防ぐため）。顔の正本は`_reference/ref-A〜D`の4枚を切り抜かずにそのまま添付する。

## 新しい参考画像を追加する手順

1. このフォルダに画像を保存し、わかりやすいファイル名にリネーム（pose-連番-内容slug.png）
2. 上記の表、および`hotpepper-image-cycle-design.md`の①ポーズローテーション表に1行追記
3. git commit・push
