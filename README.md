# TinyEditor

## Usage

Paste the following code into your browser address bar:

	light mode
    data:text/html,<body class="w-100 h-100 ma0" oninput="i.srcdoc=h.value+'<style>@import url(https://unpkg.com/tachyons/css/tachyons.min.css);'+c.value+'</style><script>'+j.value+'</script>'"><style>@import url(https://unpkg.com/tachyons/css/tachyons.min.css);.h-33{height:33.33%}</style><textarea class="w-third h-33 fl code f5" placeholder=HTML id=h></textarea><textarea class="w-third h-33 fl code f5" placeholder=CSS id=c></textarea><textarea class="w-third h-33 fl code f5" placeholder=JS id=j></textarea><iframe class="w-100 min-vh-100 bn" id=i></iframe><button class="fixed top-0 right-0" onclick="prompt('','https://itty.bitty.site/#/data:text/html;charset=utf-8,'+i.srcdoc)">...
	
	dark mode:
	data:text/html,<body class="w-100 h-100 ma0"oninput="i.srcdoc=h.value+'<style>@import url(https://unpkg.com/tachyons/css/tachyons.min.css);'+c.value+'</style><script>'+j.value+'</script>'"><style>@import url(https://unpkg.com/tachyons/css/tachyons.min.css);.h-33{height:33.33%}</style><textarea class="bg-black-80 white b--black-80 w-third h-33 fl code f5" placeholder=HTML id=h></textarea><textarea class="bg-black-80 white b--black-80 w-third h-33 fl code f5" placeholder=CSS id=c></textarea><textarea class="bg-black-80 white b--black-80 w-third h-33 fl code f5" placeholder=JS id=j></textarea><iframe class="w-100 min-vh-100 bn" id=i></iframe><button class="bg-black-80 white b--black-80 fixed top-0 right-0" onclick="prompt('','https://itty.bitty.site/#/data:text/html;charset=utf-8,'+i.srcdoc)">...

If you want to read the code, check out [index.html](https://github.com/laithserhan/TinyEditor/blob/master/index.html) dark mode at [index-darkmode.html](https://github.com/laithserhan/TinyEditor/blob/master/index-darkmode.html) forked from [umpox/TinyEditor](https://github.com/umpox/TinyEditor)
