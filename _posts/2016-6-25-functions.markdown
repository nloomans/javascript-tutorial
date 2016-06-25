---
layout: post
title:  "#2 Functions"
date:   2016-6-25
---
<p class="intro"><span class="dropcap">L</span>orem ipsum hi dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

{% highlight javascript %}
document.querySelector('#title').innerText = 'Hello World!';
{% endhighlight %}

Zoals je kunt zien, de `<h1 id="title">Javascript Tutorial</h1>` word vervangen door een `<h1 id="title">Hello World!</h1>`.

Laten we de coden in stukes breken. Eerst hebben we `document.querySelector('#title')`, `querySelector` is een comando die html elementen selecteerd. Tussen de ronden haakjes geven we een CSS Selector mee. Hierna hebben we `.innerText`
