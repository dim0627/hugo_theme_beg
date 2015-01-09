---
slug: "about-aglaus-ja"
title: "Aglausについて"
eyecatch: "hugo.png"
date: 2015-01-06
comments: true
tags: ["hugo", "golang", "aglaus"]
---

## Hugo用テーマ[Aglaus]について

[Aglaus](https://github.com/dim0627/hugo_theme_aglaus)はGolangで書かれた静的サイトジェネレータ、[Hugo](http://gohugo.io)用のテーマです。

導入方法については[Aglaus](https://github.com/dim0627/hugo_theme_aglaus)の`README.md`を参照してください。

### コメント

[Disqus](https://disqus.com/)が導入出来ます。

`config.yaml`の`Disqus`を設定し、記事のMarkdownに`comments: true`を設定してください。

[<img src="/hugo_theme_aglaus/images/desc_disqus.png" class="image" alt="disqus">](/hugo_theme_aglaus/images/desc_disqus.png)

設定されなかった場合、コメント欄は表示されません。

特定の記事のみコメントを拒否する場合は、`comments`を未設定にするか、`false`を設定してください。

``` markdown
---
title: "about-aglaus"
date: 2015-01-06
comments: false
---

## About hugo theme [Aglaus]
 :
 :
```

### アイキャッチ画像

記事単位にアイキャッチ画像が設定出来ます。

[<img src="/hugo_theme_aglaus/images/desc_eyecatch.png" class="image" alt="eyecatch">](/hugo_theme_aglaus/images/desc_eyecatch.png)

記事のMarkdownファイルに`eyecatch`を設定し、`static/images/`以下に画像を配備してください。

``` markdown
---
title: "about-aglaus"
eyecatch: "hugo.png"
date: 2015-01-06
---

## About hugo theme [Aglaus]
 :
 :
```

不要な場合は記述を削除することでデフォルト画像が表示されます。

### タギング

`tags`を設定することで、記事にタグをつけることが出来ます。

``` markdown
---
title: "about-aglaus"
date: 2015-01-06
tags: ["hugo", "aglaus"]
---

## About hugo theme [Aglaus]
 :
 :
```

タグは記事個別ページの下部に表示され、関連する投稿のインデクシングに利用されます。

[<img src="/hugo_theme_aglaus/images/desc_tags.png" class="image" alt="tags">](/hugo_theme_aglaus/images/desc_tags.png)

### 関連する投稿

タグを基準に関連する投稿を表示します。

[<img src="/hugo_theme_aglaus/images/desc_tags.png" class="image" alt="tags">](/hugo_theme_aglaus/images/desc_tags.png)

`config.yaml`の`ShowRelatedPost`を`False`にすることで非表示にできます。

その場合、タグも表示されなくなります。

### プロフィール

ページ下部にプロフィールを表示出来ます。

[<img src="/hugo_theme_aglaus/images/desc_profile.png" class="image" alt="profile">](/hugo_theme_aglaus/images/desc_profile.png)

表示する情報は[Gravatar](https://gravatar.com/)から取得しているため、`config.yaml`に`GravatarHash`を設定する必要があります。

ハッシュの取得については[Creating the Hash](https://ja.gravatar.com/site/implement/hash/)を参照してください。

設定がない場合、プロフィールは表示されません。

### ソーシャルリンク

プロフィールに[Facebook](https://www.facebook.com/)、[Twitter](https://twitter.com/)、[GitHub](https://github.com/)のリンクを配置出来ます。

[<img src="/hugo_theme_aglaus/images/desc_profile.png" class="image" alt="profile">](/hugo_theme_aglaus/images/desc_profile.png)

`config.yaml`に`Facebook`、`Twitter`、`Github`のIDを設定する必要があります。

設定がない場合、リンクは表示されません。

### シェアボタン

ページ最下部にシェアボタンが表示されます。

[<img src="/hugo_theme_aglaus/images/desc_share.png" class="image" alt="share">](/hugo_theme_aglaus/images/desc_share.png)

[SHAREBUTTON](http://sharebutton.net/)のプラグインを利用しています。

## お問い合わせ

[https://www.facebook.com/daisuke.tsuji.735](https://www.facebook.com/daisuke.tsuji.735)

[https://twitter.com/dim0627](https://twitter.com/dim0627)

