<html>
<head>
<title>main.py</title>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8">
<style type="text/css">
.s0 { color: #808080;}
.s1 { color: #a9b7c6;}
.s2 { color: #6a8759;}
.s3 { color: #6897bb;}
.s4 { color: #cc7832;}
</style>
</head>
<body bgcolor="#2b2b2b">
<table CELLSPACING=0 CELLPADDING=5 COLS=1 WIDTH="100%" BGCOLOR="#606060" >
<tr><td><center>
<font face="Arial, Helvetica" color="#000000">
main.py</font>
</center></td></tr></table>
<pre><span class="s0"># simles</span>
<span class="s0">#rápido</span>
<span class="s0"># our main python:</span>
<span class="s1">bank1 = input(</span><span class="s2">&quot;banco numero 1:insira as informações como nomes que deseja armazenar aqui:&quot;</span><span class="s1">)</span>
<span class="s1">bank2 = input(</span><span class="s2">&quot;banco numero 2:insira as informações como senhas que deseja armazenar aqui:&quot;</span><span class="s1">)</span>
<span class="s1">bank3 = input(</span><span class="s2">&quot;banco numero 3:insira as informações como emails que deseja armazenar aqui:&quot;</span><span class="s1">)</span>
<span class="s1">var = </span><span class="s3">0</span>
<span class="s1">the_switch = [var</span><span class="s4">,</span><span class="s1">bank1</span><span class="s4">,</span><span class="s1">bank2</span><span class="s4">,</span><span class="s1">bank3]</span>
<span class="s1">comand = input(</span><span class="s2">&quot;coloqueo o nome e o numero do seu banco de dados:&quot;</span><span class="s1">)</span>
<span class="s4">if </span><span class="s1">comand == </span><span class="s2">&quot;banco numero 1&quot;</span><span class="s1">:</span>
    <span class="s1">print(</span><span class="s2">&quot;your name:&quot;</span><span class="s4">,</span><span class="s1">the_switch[</span><span class="s3">1</span><span class="s1">])</span>
<span class="s4">if </span><span class="s1">comand == </span><span class="s2">&quot;banco numero 2&quot;</span><span class="s1">:</span>
    <span class="s1">print(</span><span class="s2">&quot;your password:&quot;</span><span class="s4">,</span><span class="s1">the_switch[</span><span class="s3">2</span><span class="s1">])</span>
<span class="s4">if </span><span class="s1">comand == </span><span class="s2">&quot;banco numero 3&quot;</span><span class="s1">:</span>
    <span class="s1">print(</span><span class="s2">&quot;your email:&quot;</span><span class="s4">,</span><span class="s1">the_switch[</span><span class="s3">3</span><span class="s1">])</span></pre>
</body>
</html>
