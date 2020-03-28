# Enclass+ 外出自粛モブプロ


## 参加者
- さきちょ
- やましょ
- なる

## 使用技術
- vue.js
- Element UI (https://element.eleme.io/#/en-US/component/installation)
- css

## 要件
- 最新ニュースの情報のリンクがまとまってるサイト

- ページアクセスした時に、最新ニュースが表示される
  - 8件表示(２行4列)
- 検索フォームのinputを監視する
  - 入力が止まったらAPIを走らせて検索

## 資料
ワイヤーフレーム
https://www.figma.com/file/E4r9C1PSGCSukFQqMNm8j6/Untitled?node-id=0%3A1
Qiita API
https://qiita.com/api/v2/docs#get-apiv2items

## 作業経過
- 13:25~13:30 さきちょ
  - Vue.js導入
  - Element UI導入
- 13:33~13:38 やましょ
  - 無力
- 13:38~13:45 なる
  - v-forを用いた結果一覧表示
- 13:45~13:50 さきちょ
  - v-forを用いた結果一覧表示

## 残りのTODO
- ページ初期表示時に検索を実行
- 結果リストにリンクを付与(Qiitaのページに飛べるように)
- ヘッダーCSS
- カードCSS

### WANTS
- 入力するだけで検索実行
- show loading