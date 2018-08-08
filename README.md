# TinyEditor

## Usage

Paste the following code into your browser address bar:

    data:text/html,<body oninput="i.srcdoc=h.value+'<style>'+c.value+'</style><script>'+j.value+'<\/script>'"><style>textarea,#i{width:100%;height:50%}*{margin:0}textarea{width:33.33%;font-size:18}</style><textarea placeholder=HTML id=h></textarea><textarea placeholder=CSS id=c></textarea><textarea placeholder=JS id=j></textarea><iframe id=i>

If you want to read the code, check out [index.html](https://github.com/umpox/TinyEditor/blob/master/index.html)
