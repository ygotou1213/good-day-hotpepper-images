# デザインパターン参考画像ライブラリ

背景パターン・ネイルデザインパターンの参考画像を格納する。ユーザーが画像を共有した際はここに保管し、
`hotpepper-image-cycle-design.md`のレパートリー表に追記する。

## フォルダ構成

- `nail-art/general/` — 季節を問わない汎用ネイルデザインパターン（色だけ月次パレットに差し替えて使う）
- `nail-art/{spring,summer,autumn,winter}/` — 季節限定のネイルデザインパターン
- `background/{spring,summer,autumn,winter}/` — 季節ごとの背景パターン

## 現在の登録パターン

### nail-art/general/

| パターン名 | ファイル | 出典 | 適用メニュー |
|---|---|---|---|
| ミネラルアート（天然石・大理石調＋ゴールドフォイル） | `mineral-art-01〜05*.png` | MARIE NAILS / Narym nail art / ayu.naily / nail art by Moli / MINERAL ART DESIGN（2026-07-26ユーザー共有） | 定額アート、持ち込み |

## 新しい参考画像を追加する手順

1. 該当フォルダ（季節 or general、nail-art or background）に画像を保存
2. わかりやすいファイル名にリネーム（パターン名-連番-出典.png）
3. 上記の表、および`hotpepper-image-cycle-design.md`のレパートリー表に1行追記
4. git commit・push
