# TinyEditor

## Usage

Paste the following code into your browser address bar:

light mode:

```html
data:text/html,<body class="w-100 h-100 ma0" oninput="i.srcdoc=h.value+'<style>@import url(https://unpkg.com/tachyons/css/tachyons.min.css);'+c.value+'</style><script>'+j.value+'</script>'"><style>@import url(https://unpkg.com/tachyons/css/tachyons.min.css);.h-33{height:33.33%}</style><textarea class="w-third h-33 fl code f5" placeholder=HTML id=h></textarea><textarea class="w-third h-33 fl code f5" placeholder=CSS id=c></textarea><textarea class="w-third h-33 fl code f5" placeholder=JS id=j></textarea><iframe class="w-100 min-vh-100 bn" id=i></iframe><button class="absolute top-0 right-0" onclick="prompt('','https://itty.bitty.site/#/data:text/html;charset=utf-8,'+i.srcdoc)">...
```

dark mode:

```html
data:text/html,<body class="w-100 h-100 ma0"oninput="i.srcdoc=h.value+'<style>@import url(https://unpkg.com/tachyons/css/tachyons.min.css);'+c.value+'</style><script>'+j.value+'</script>'"><style>@import url(https://unpkg.com/tachyons/css/tachyons.min.css);.h-33{height:33.33%}</style><textarea class="bg-black-80 white b--black-80 w-third h-33 fl code f5" placeholder=HTML id=h></textarea><textarea class="bg-black-80 white b--black-80 w-third h-33 fl code f5" placeholder=CSS id=c></textarea><textarea class="bg-black-80 white b--black-80 w-third h-33 fl code f5" placeholder=JS id=j></textarea><iframe class="w-100 min-vh-100 bn" id=i></iframe><button class="bg-black-80 white b--black-80 absolute top-0 right-0" onclick="prompt('','https://itty.bitty.site/#/data:text/html;charset=utf-8,'+i.srcdoc)">...
```

If you want to read the code, check out [index.html](https://github.com/laithserhan/TinyEditor/blob/master/index.html) dark mode at [index-darkmode.html](https://github.com/laithserhan/TinyEditor/blob/master/index-darkmode.html) forked from [umpox/TinyEditor](https://github.com/umpox/TinyEditor)

### Examples

random unsplash image website:

```html
https://itty.bitty.site/#/data:text/html;charset=utf-8,<body class="ma0 pa0"><div class="page bg-red w-100 min-vh-100 pa6"><h1 class="f1 white fw1 tc small-caps tracked">Random Unsplash Image Website</h1><hr class="b--white-50 mv6"><h2 class="f5 fw1 tc small-caps tracked no-underline yellow pb2" onClick="window.location.href=window.location.href">Load Another Random Unsplash Image...</h2><div class="w-two-thirds center pv4"><img class="w-100" src="https://source.unsplash.com/random"/></div><h3 class="f5 white fw1 tc small-caps tracked pt6">Webite by <a class="no-underline yellow" href="http://laithserhan.github.io/">Laith Serhan</a></h3><h3 class="f5 white fw1 tc small-caps tracked">Images from <a class="no-underline yellow" href="https://unsplash.com/">Unsplash.com</a></h3><h3 class="f5 white fw1 tc small-caps tracked">Created with <a class="no-underline yellow" href="https://github.com/laithserhan/TinyEditor/">TinyEditor</a></h3><h3 class="f5 white fw1 tc small-caps tracked">Served with <a class="no-underline yellow" href="http://about.bitty.site/">itty.bitty.site</a></h3></div></body><style>@import url(https://unpkg.com/tachyons/css/tachyons.min.css);</style><script></script>
```
