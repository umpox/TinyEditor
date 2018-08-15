# TinyEditor

## Usage

Paste the following code into your browser address bar:

	data:text/html,<body oninput="i.srcdoc=`${H.value}<script>${J.value}</script><style>${C.value}`"><style>*{width:100%;margin:0;font-size:18}.t{width:33.33%}.t,#i{height:50%}</style><script>var y=x=>`<textarea class=t id=${x[0]} placeholder=${x}></textarea>`;document.write(y('HTML')+y('CSS')+y('JS')+'<iframe id=i>');</script>

If you want to read the code, check out [index.html](https://github.com/umpox/TinyEditor/blob/master/index.html)
