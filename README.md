# AXT-web

綾急技研のwebサイトリポジトリです。

## 簡易サイトマップ

```
https://axtech.dev/
    _ref/
        style.css ------------------------------- 共通スタイルシート
        script.js ------------------------------- 共通スクリプト
        sidebar.html ---------------------------- script.jsに書くためのサイドバーHTML
    _bg/
        [num].jpg ------------------------------- 各ページの背景画像スライドショーでn番目に見せる写真
    _img/
        logo.svg -------------------------------- AXT-Logoのal-Cw.svgを持ってきてます
    introduction/
        index.html ------------------------------ 綾急技研の紹介(グループ理念、活動内容など)
    member/
        index.html ------------------------------ メンバー紹介TOP
        [name].html ----------------------------- メンバーの個人ページ
    license/
        index.html ------------------------------ AeTOSの全文と簡単な説明
    contact/
        index.html ------------------------------ 綾急技研やメンバーへのお問い合わせ
    article/
        img/
            [articleID]-[imgNum].jpg ------------ [articleID].htmlで使う[imgNum]番目の画像
        index.html ------------------------------ 記事一覧(新着n件のみ表示)
        index_all.html ------------------------------ 記事一覧(すべて表示)
        [articleID].html ------------------------ 技研ブログなど。[articleID]は「K~Zの英大文字1文字 + 36進数(小文字)4桁」
    index.html ---------------------------------- 技研webのTOP
```

