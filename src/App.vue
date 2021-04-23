<template>
  <div id="app">
    <div id="nav">
    </div>
    <router-view/>
  </div>
</template>

<style>
html, body, div, span, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
abbr, address, cite, code,
del, dfn, em, img, ins, kbd, q, samp,
small, strong, sub, sup, var,
b, i,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, figcaption, figure,
footer, header, hgroup, menu, nav, section, summary,
time, mark, audio, video {
    margin:0;
    padding:0;
    border:0;
    outline:0;
    font-size:100%;
    vertical-align:baseline;
    background:transparent;
}

body {
  line-height: 1;
}
article,/*ニュースやブログ記事など、サイト内で自己完結していて、それ自体が独立したコンテンツとして成り立つもの。*/
aside,
details,figcaption,figure,
footer,header,hgroup,menu,nav,section{
  display: block;
}
nav ul{
  list-style: none;
}

blockquote/*引用・転載文であることを示すタグ*/,q/*q>タグは、他の情報源からの引用句・引用文であることを表す際に使用します。*/{
  quotes: none;
  /*↑開始記号、終了記号指定*/
}

a {
    margin:0;
    padding:0;
    font-size:100%;
    vertical-align:baseline;/*揃え位置初期値*/
    background:transparent;
}

/* change colours to suit your needs */

ins /*INS」とは「insert」の略で、後から追加された部分を示すタグです*/
{
    background-color:#ff9;
    color:#000;
    text-decoration:none;
}

/* change colours to suit your needs */
mark /*<mark>タグは、文書内の該当テキストをハイライトして目立たせる際に使用します。*/
{
    background-color:#ff9;
    color:#000;
    font-style:italic;
    font-weight:bold;
}

del /*一般的なブラウザでは、<DEL>～</DEL>で囲まれた部分に打ち消し線が付きます。*/
{
    text-decoration: line-through;
}

abbr[title], /*略語や頭字語であることを表す際に使用します。*/
dfn[title]/*用語が使用されていることを示す際に使用します*/ {
    border-bottom:1px dotted;
    cursor:help;
}

table{
  border-collapse:collapse;/*セルのボーダーの表示の仕方を指定する*/
}

/* change border colour to suit your needs */
hr /*段落の区切り*/{
    display:block;
    height:1px;
    border:0;  
    border-top:1px solid #cccccc;
    margin:1em 0;
    padding:0;
}

input, select {
    vertical-align:middle;/*行のなかでのテキストや画像などの縦方向の揃え位置を指定する際に使用します。*/
}

html {
  background-color: #15202b;
}

* {
  color: white;
  font-family: "Noto Sans JP";
}

</style>




