# TinyEditor

## Usage

Paste the following code into your browser address bar:

    data:text/html,<style>body{margin:0}[id]{width:33.33%;height:50%}#i{width: 100%}</style><body oninput="i.srcdoc=h.value+'<style>'+c.value+'</style><script>'+j.value+'</script>'"><textarea placeholder=HTML id=h></textarea><textarea placeholder=CSS id=c></textarea><textarea placeholder=JS id=j></textarea><iframe id=i>
    
If you want to read the code, check out [index.html](https://github.com/ZweiZhao/TinyEditor/blob/master/index.html)
