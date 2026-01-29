# zoo-Shop
ILEGAL SHOP
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<title>Zoo Shop</title>
<style>
body { font-family: Arial; background:#f2f2f2; margin:0; }
header { background:#2196f3; color:white; padding:15px; text-align:center; }
.produk, .keranjang {
  background:white;
  margin:15px;
  padding:15px;
  border-radius:10px;
}
button {
  background:#2196f3;
  color:white;
  border:none;
  padding:8px 12px;
  border-radius:5px;
}
button.hapus { background:red; }
</style>
</head>

<body>

<header>
  <h1>Zoo Shop</h1>
  <p>Keranjang: <span id="jumlah">0</span> item</p>
</header>

<div class="produk">
  <h3>Kaos</h3>
  <p>Rp 50.000</p>
  <button onclick="tambah('Kaos', 5
