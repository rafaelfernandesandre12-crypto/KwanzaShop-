index.html
<!DOCTYPE html>
<html>
<head>
<title>KwanzaShop</title>
<meta name="viewport" content="width=device-width, initial-scale=1">

<style>
body{
font-family:Arial;
background:#f5f5f5;
text-align:center;
}

header{
background:black;
color:white;
padding:15px;
}

.produto{
background:white;
margin:20px;
padding:15px;
border-radius:10px;
}

button{
background:green;
color:white;
padding:10px;
border:none;
border-radius:5px;
}
</style>
</head>

<body>

<header>
<h1>KwanzaShop 🇦🇴</h1>
<p>Sua loja online angolana</p>
</header>

<div class="produto">
<h2>Tênis Nike</h2>
<p>Preço: 10.000 Kz</p>
<button onclick="comprar('Tênis Nike')">Comprar</button>
</div>

<div class="produto">
<h2>Telemóvel Samsung</h2>
<p>Preço: 120.000 Kz</p>
<button onclick="comprar('Samsung')">Comprar</button>
</div>

<script>
function comprar(produto){
window.open("https://wa.me/244SEUNUMERO?text=Quero comprar " + produto);
}
</script>

</body>
</html>
