<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<script>
$(document).ready(function() {
	code_list=document.getElementsByTagName("pre");
	for(var i=0;i<code_list.length;i++) {
		code_list[i].load(code_list[i].getAttribute("file"));
	}
});

</script>

<pre id="sample" file="sample.py"></pre>
<pre file="main.c"></pre>
