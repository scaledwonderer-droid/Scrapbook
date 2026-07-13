# FFXIV Adventurer's Scrapbook

旅人の机の上に写真やメモ、旅券、宿のレシートを広げたような、スクラップブック風のFFXIV向けプロフィール画像を作成できます。

- 公開ページ：https://scaledwonderer-droid.github.io/Scrapbook/
- 元リポジトリ：https://github.com/scaledwonderer-droid/Scrapbook
- 初公開：2026年
- 企画・デザイン・制作：鱗の旅人

## 主な機能

- 1920×1080px（16:9）のPNG画像を生成
- Canvas上のプレビューと保存画像を同じ内容で描画
- キャラクターSSと小写真2枚をアップロード可能
- キャラクターSSと小写真はドラッグによる位置調整、ズーム調整に対応
- キャラクター名、DC / World、Main Jobを表示
- 日本・北米・欧州・オセアニアのWorld選択に対応
- 選択肢にないDC / Worldは自由入力可能
- 任意のQRコード画像を表示可能
- QRコード未設定時は石・結晶風の装飾を表示
- Active Time、VC、使用言語をInn Receiptへ表示
- 小写真ごとにキャプションと文字色を設定可能
- 5種類の手書き風フォントから選択可能
- 背景や入力内容をブラウザ内だけで処理
- 外部ライブラリ不使用

## Traveler Area

Traveler Areaは、次の2種類から選択できます。

### 自由メモ

日本語を含む自由記入に対応しています。

- 全角10文字×5行程度を想定
- 最大5行まで表示
- 自動折り返し
- 選択中の手書き風フォントを反映

### スタンプ

プレイスタイルや主な活動内容を、旅行手帳に押したようなPNGスタンプで表示できます。

- 最大6個まで選択可能
- 選択数に合わせて自動配置
- 透過PNGによるゴム印風デザイン
- 15種類を収録

収録スタンプ：

- CASUAL
- STORY
- BATTLE
- HIGH-END
- PvP
- GPOSE
- HOUSING
- CRAFTING
- GATHERING
- FISHING
- TREASURE MAP
- DEEP DUNGEON
- ROLEPLAY
- SOCIAL
- PERFORMANCE

## フォント

入力した文字には、次のフォントを選択できます。

- Dancing Script
- Klee One
- Zen Kurenaido
- Zen Maru Gothic
- Hachi Maru Pop

初期設定は **Klee One** です。

Dancing Scriptを選択した場合、日本語部分はKlee Oneへフォールバックします。

各フォントのライセンス文は `fonts/` フォルダ内に収録しています。

## 使い方

1. キャラクターSSをアップロードします。
2. キャラクター名、DC / World、Main Jobを入力します。
3. 必要に応じてQRコード、小写真、キャプションを設定します。
4. Traveler Areaで「自由メモ」または「スタンプ」を選択します。
5. Active Time、VC、使用言語を設定します。
6. プレビュー上でキャラクターSSと小写真の位置やズームを調整します。
7. 「PNG保存」ボタンから完成画像を保存します。

## プライバシー

アップロードした画像や入力内容は、利用者のブラウザ内だけで処理されます。

本ツールには、画像や入力内容をサーバーへ送信・保存する機能はありません。

## ファイル構成

```text
README.md
index.html
scrapbook_base_back.png
fonts/
  DancingScript.ttf
  HachiMaruPop-Regular.ttf
  KleeOne-Regular.ttf
  ZenKurenaido-Regular.ttf
  ZenMaruGothic-Regular.ttf
  OFL-DancingScript.txt
  OFL-HachiMaruPop.txt
  OFL-KleeOne.txt
  OFL-ZenKurenaido.txt
  OFL-ZenMaruGothic.txt
stamps/
  battle.png
  casual.png
  crafting.png
  deep-dungeon.png
  fishing.png
  gathering.png
  gpose.png
  high-end.png
  housing.png
  performance.png
  pvp.png
  roleplay.png
  social.png
  story.png
  treasure-map.png
```

`index.html`、`scrapbook_base_back.png`、`fonts/`、`stamps/` の位置関係を変更すると、背景・フォント・スタンプを読み込めなくなる場合があります。

## 制作者表記

本作の企画・デザイン・制作は **鱗の旅人** によるものです。

本リポジトリ以外で同一または改変された内容を見かけた場合は、元リポジトリと公開履歴をご確認ください。

## 注意事項

SQUARE ENIXおよびFINAL FANTASY XIV公式とは関係ありません。

公式素材・公式アイコンは使用していません。収録スタンプは、一般的な題材をもとに制作したオリジナル図柄です。

生成画像を利用する際は、FINAL FANTASY XIVの利用規約、素材利用条件、各コミュニティのルールをご確認ください。

FINAL FANTASY XIV © SQUARE ENIX
