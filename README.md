# css_MenuObi
マウスオーバー時に折り返しの帯のような見せ方がCSSのみで表現


[Demo](http://style-type.net/githubDemo/cssmenuobi/index.html)


## transitionによるCSSアニメーションの問題を解消する方法
### js(jQuery)
`<script src="js/preload.js"></script>`

### css
    .preload * {
            -webkit-transition: none !important;
            -moz-transition: none !important;
            -ms-transition: none !important;
            -o-transition: none !important;
            transition: none !important;
      }

### 参考サイト
[transitionによるCSSアニメーションがChromeでページ読み込み時に動作してしまう問題](http://14-00.com/archives/31)



