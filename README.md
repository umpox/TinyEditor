# TinyEditor

## Usage

Paste the following code into your browser address bar:

    data:text/html,<body oninput="I.srcdoc=H.value+'<style>'+C.value+'</style><script>'+J.value+'</script>'"><style>[id]{width:33%;height:50%}#I{width:99%}</style><script>document.write('HTML CSS JS '.replace(/(.)\w+ /g,'<textarea placeholder=$&id=$1></textarea>'))</script><iframe id=I>

If you want to read the code, check out [index.html](./index.html)
