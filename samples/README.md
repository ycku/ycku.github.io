<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<script src="//cdnjs.cloudflare.com/ajax/libs/highlight.js/9.4.0/languages/go.min.js"></script>
<script src="https://highlightjs.org/static/highlight.pack.js"></script>
<script>
$(document).ready(function() {
	code_list=document.getElementsByTagName("code");
	for(var i=0;i<code_list.length;i++) {
		$(code_list[i]).load(code_list[i].getAttribute("file"));
	}
	hljs.initHighlighting();
});

</script>

<pre><code id="sample" file="sample.py" class="python"></code></pre>
<pre><code file="main.c" class="c"></code></pre>
