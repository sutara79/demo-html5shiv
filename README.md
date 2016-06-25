# html5shivの検証

下記のプラグインを検証します。

- GitHub: https://github.com/aFarkas/html5shiv
- CDN: https://cdnjs.com/libraries/html5shiv

- - -
下記のページをIE8で開いてみてください。  
各要素が色付けされ、`<header>`と`<article>`の中に子要素が動的に追加されるはずです。

http://sutara79.github.io/demo-html5shiv/01.html

html5shivを使わないと、HTML5の要素を操作できません。

http://sutara79.github.io/demo-html5shiv/02.html

なお、HTML5のタグを使わずに`<div class="header">`のように代用すれば、当然ですがCSSでもJavaScriptでも問題ありません。

http://sutara79.github.io/demo-html5shiv/03.html

- - -
### 結論
html5shivを導入すれば、HTML5タグを遠慮なく使えます。