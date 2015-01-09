---
title: "about-aglaus"
eyecatch: "hugo.png"
date: 2015-01-06
comments: true
tags: ["hugo", "golang", "aglaus"]
---

## About hugo theme [Aglaus]

[Aglaus](https://github.com/dim0627/hugo_theme_aglaus) is theme for [Hugo](http://gohugo.io).

Please refer to the `README.md` of [Aglaus] (https://github.com/dim0627/hugo_theme_aglaus) for introduction method.

### Comment

You can use [Disqus](https://disqus.com/).

Set `Disqus` to `config.yaml`, and set `comments: true` to Markdown.

[<img src="/hugo_theme_aglaus/images/desc_disqus.png" class="image" alt="disqus">](/hugo_theme_aglaus/images/desc_disqus.png)

If you did not set, the comments section is not displayed.

If you want to deny a comment only particular article, you can either unset the `comments`, please set the `false`.

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

### Eyecatch image

Eye-catching image can be set to the article unit.

[<img src="/hugo_theme_aglaus/images/desc_eyecatch.png" class="image" alt="eyecatch">](/hugo_theme_aglaus/images/desc_eyecatch.png)

Set the `eyecatch` to Markdown file of articles, please deploy the image to `static/images/` below.

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

If you did not set, default image is displayed.

### Tag

By setting the `tags`, you can tag the article.

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

Tag is displayed at the bottom of the article individual pages, will be used in the indexing of related posts.

[<img src="/hugo_theme_aglaus/images/desc_tags.png" class="image" alt="tags">](/hugo_theme_aglaus/images/desc_tags.png)

### Related Post

Display posts associated with the reference tags.

[<img src="/hugo_theme_aglaus/images/desc_tags.png" class="image" alt="tags">](/hugo_theme_aglaus/images/desc_tags.png)

You can hide it by the `ShowRelatedPost` of `config.yaml` to `False`.

In that case, also will not be displayed tag.

### Profile

Profile is displayed at the bottom of the page.

[<img src="/hugo_theme_aglaus/images/desc_profile.png" class="image" alt="profile">](/hugo_theme_aglaus/images/desc_profile.png)

Information of profile getting from [Gravatar](https://gravatar.com/).

Please set the `GravatarHash` to `config.yaml`.

Please refer to the [Creating the Hash](https://ja.gravatar.com/site/implement/hash/) for hash of the acquisition.

If you did not set, profie is not displayed.

### Social Links

You can place a link on [Facebook](https://www.facebook.com/) and [Twitter](https://twitter.com/) and [GitHub](https://github.com/).

[<img src="/hugo_theme_aglaus/images/desc_profile.png" class="image" alt="profile">](/hugo_theme_aglaus/images/desc_profile.png)

You need to set the ID of the 'Facebook' and 'Twitter' and 'Github' to 'config.yaml'.

### Share Buttons

Share buttons is displayed at the bottom of the page.

[<img src="/hugo_theme_aglaus/images/desc_share.png" class="image" alt="share">](/hugo_theme_aglaus/images/desc_share.png)

Using the plugin [SHAREBUTTON](http://sharebutton.net/).

## Contact Me

[https://www.facebook.com/daisuke.tsuji.735](https://www.facebook.com/daisuke.tsuji.735)

[https://twitter.com/dim0627](https://twitter.com/dim0627)
