<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<script src="https://highlightjs.org/static/highlight.pack.js"></script>
<script>hljs.initHighlightingOnLoad();</script>
<script>
$(document).ready(function() {
	code_list=document.getElementsByTagName("code");
	for(var i=0;i<code_list.length;i++) {
		$(code_list[i]).load(code_list[i].getAttribute("file"));
	}
	hljs.initHighlighting();
});

</script>

<pre><code id="sample" file="sample.py" class="Python"></code></pre>
<pre><code file="main.c" class="c"></code></pre>
<pre><code class="php">
$var="Hello World";
print $var;
</code></pre>
