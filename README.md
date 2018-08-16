# TinyEditor

## Usage

Paste the following code into your browser address bar:

	data:text/html,<body oninput="i.srcdoc=`${H.value}<script>${J.value}</script><style>${C.value}`"><style>*{width:100%;margin:0}[t]{width:33.33%}[id]{height:50%}</style><script>document.write('HTML,CSS,JS,<iframe id=i>'.replace(/((.).+?),/g,'<textarea placeholder=$1 id=$2 t></textarea>'))</script>


If you want to read the code, check out [index.html](https://github.com/umpox/TinyEditor/blob/master/index.html)