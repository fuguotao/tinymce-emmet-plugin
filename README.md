tinymce-emmet-plugin
====================

<blockquote><p>A TinyMCE plugin that provides an HTML editor including all <a href="https://github.com/emmetio/emmet" target="_blank">Emmet</a> features (formerly Zen Coding).</p></blockquote>

First and foremost, I really must give credit to Sergey Chikuyonok (of Emmet fame) and the good folk of <a href="http://codemirror.net/" target="_blank">CodeMirror</a>.
All I did was wrap both libraries up in a TinyMCE plugin ;-)

##Getting started
```js
tinymce.init({
	selector: '#editor',
	plugins: 'emmet',
	width: 800,
	height: 400
});
```

##Roadmap
...

##Support
Written for TinyMCE 4.x and tested in: ...
I have written this plugin in a couple hours, so please report issues if you find any.
Make sure to check out the browser support of <a href="http://codemirror.net/#browsersupport">CodeMirror</a> as well if you run into any problems.

##License
Copyright (c) 2013 e-sites Licensed under the MIT license.
