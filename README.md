<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Manuel Store | Pase BOOYAH</title>

<style>
body{
    margin:0;
    font-family: Arial, sans-serif;
    background: linear-gradient(135deg,#000000,#0f2027,#203a43,#2c5364);
    color:white;
    text-align:center;
}

/* LOGO */
.logo{
    margin-top:20px;
}

.logo img{
    width:220px;
    border-radius:10px;
}

/* TITULO */
h1{
    margin-top:10px;
    font-size:32px;
}

/* TARJETA */
.card{
    background:rgba(0,0,0,0.6);
    margin:40px auto;
    padding:30px;
    border-radius:15px;
    width:90%;
    max-width:400px;
    box-shadow:0 0 20px rgba(0,255,200,0.3);
}

/* PRECIO */
.precio{
    font-size:45px;
    color:#00ffcc;
    margin:20px 0;
    font-weight:bold;
}

/* BOTON */
button{
    padding:15px 25px;
    font-size:18px;
    background:#00ffcc;
    border:none;
    border-radius:10px;
    cursor:pointer;
    font-weight:bold;
    transition:0.3s;
}

button:hover{
    background:#00ccaa;
    transform:scale(1.05);
}

/* FOOTER */
footer{
    margin-top:40px;
    padding:15px;
    background:#000;
    font-size:14px;
}
</style>
</head>

<body>

<div class="logo">
    <img src="logo.jpg" alt="Manuel Store">
</div>

<h1>🔥 PASE BOOYAH 🔥</h1>

<div class="card">
    <p>Compra rápida y segura</p>
    <div class="precio">15 Bs</div>
    <button onclick="comprar()">Comprar por WhatsApp</button>
</div>

<footer>
© 2026 Manuel Store - Bolivia
</footer>

<script>
function comprar(){
window.open("https://wa.me/59169959830?text=Hola%20quiero%20comprar%20el%20Pase%20BOOYAH%20de%2015Bs","_blank");
}
</script>

</body>
</html>
