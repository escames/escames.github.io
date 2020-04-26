
# Testando 

Melhor organização da UNICAMP [ESF](http://limeira.esf.org.br/)

# Em breve novidades

<head>
  <script data-ad-client="ca-pub-7662484566308519" async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js">
  </script>
</head>

<head>
<script type="text/javascript">
function countDown(secs) {
    var btn = document.getElementById('btn');
    btn.value = "Aguarde "+secs+" segundos";<!--texto que aparecerá enquanto o tempo descer, não altere o"+secs+"-->
    if(secs < 1) {
        clearTimeout(timer);
        btn.disabled = false;
        btn.value = 'OK clique aqui';
    }
    secs--;
    var timer = setTimeout('countDown('+secs+')',1000);
}
</script>
</head>
<body>
<input disabled type="submit" id="btn" value="Aguarde 50 segundos!"><!--texto inicial do botão-->
<script type="text/javascript">countDown(60);<!--texto inicial do botão-->
</script>
</body>

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
