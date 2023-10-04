<!DOCTYPE html>
<html>
<title>Tugas Kelompok</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://badoystudio.com/cloudme.fonts.googleapis.com/css?family=Inconsolata">
<style>
body, html {
height: 100%;
font-family: "Inconsolata", sans-serif;
}

.bgimg {
background-position: center;
background-size: cover;
background-image: url("https://i.pinimg.com/originals/2a/04/a3/2a04a3b96ce997a18781fdc5e6796817.jpg");
min-height: 75%;
}

.menu {
display: none;
}
</style>
<body>

<!-- Links (sit on top) -->
<div class="w3-top">
<div class="w3-row w3-padding w3-black">
<div class="w3-col s3">
<a href="#" class="w3-button w3-block w3-light-blue">Beranda</a>
</div>
<div class="w3-col s3">
<a href="#tentang" class="w3-button w3-block w3-blue">Informasi</a>
</div>
<div class="w3-col s3">
<a href="#menu" class="w3-button w3-block w3-light-blue">Menu</a>
</div>
<div class="w3-col s3">
<a href="#tempat" class="w3-button w3-block w3-blue">Lokasi</a>
</div>
</div>
</div>

<!-- Header + gambar -->
<header class="bgimg w3-display-container w3-grayscale-min" id="home">
<div class="w3-display-bottomleft w3-center w3-padding-large w3-hide-small">
<span class="w3-tag">Buka jam 6 puagi sampai 6 malem</span>
</div>
<div class="w3-display-middle w3-center">
<span class="w3-text-brown w3-light-grey" style="font-family: animation game ; font-size:90px">Cafe PINKA<br>"Pinggir Kali"</span>
</div>
<div class="w3-display-bottomright w3-center w3-padding-large">
<span class="w3-text-white">Jalan Buntu No.15 Kota Malang</span>
</div>
</header>

<!-- menambah bg dan teks besar ke seluruh halaman 
grayscale: buat ngewarnai full-->
<div class="w3-sand w3-grayscale w3-large">

<!-- About Container -->
<div class="w3-container" id="about">
<div class="w3-content" style="max-width:700px">
<h5 class="w3-center w3-padding-64"><span class="w3-tag w3-wide">Tentang CAFE PINKA</span></h5>
<p>Mulai dirilis pada tanggal 12 September 2023 di Kota Malang yang terletak dekat dengan kali yang mana ketika sore hari akan nampak indahnya senja.</p>
<p>Semoga dengan adanya Cafe ini bisa menambah jiwa senja kalian bersamaan dengan menikmati menu lezat dari kita.</p>
<div class="w3-panel w3-leftbar w3-light-blue">
<p><i>"Senja ter-indah hanya ada di PINKA" .</i></p>
<p>MaEl-Risma Eliza</p>
</div>
<img src="https://i.pinimg.com/originals/1f/15/5e/1f155e636d74c41acd4819f0d8c56d2b.jpg" style="width:100%;max-width:1000px" class="w3-margin-top">
<p><strong>Buka:</strong> setiap hari dari jam 6 puagi sampai 6 malem.</p>
<p><strong>Alamat:</strong> Jalan Buntu No.15 Kota Malang</p>
</div>
</div>

<!-- Menu Container -->
<div class="w3-container" id="menu">
<div class="w3-content" style="max-width:700px">

<h5 class="w3-center w3-padding-48"><span class="w3-tag w3-wide">Menu Cafe PINKA</span></h5>

<div class="w3-row w3-center w3-card w3-padding">
<a href="javascript:void(0)" onclick="openMenu(event, 'Makanan');" id="myLink">
<div class="w3-col s6 tablink">Makanan</div>
</a>
<a href="javascript:void(0)" onclick="openMenu(event, 'Minuman');">
<div class="w3-col s6 tablink">Minuman</div>
</a>
</div>

<div id="Makanan" class="w3-container menu w3-padding-48 w3-card">
<h5>Roti Canai</h5>
<p class="w3-text-grey">roti gepeng dengan rasa cenderung asin dan lembut saat digigit</p>
<p class="w3-text-blue">Rp. 12.000</p><br>

<h5>Pancake Stroberi</h5>
<p class="w3-text-grey">pancake dengan tuangan saus coklat dan buah stroberi diatasnya</p>
<p class="w3-text-blue">Rp. 15.000</p><br>

<h5>Cireng Bumbu Rujak</h5>
<p class="w3-text-grey">bertekstur kenyal dan rasa gurih dengan cocolan bumbu pedas manis</p>
<p class="w3-text-blue">Rp. 13.000</p><br>

<h5>Nasi Gila</h5>
<p class="w3-text-grey">perpaduan sosis, telur, cabai merah dan bumbu ala PINKA</p>
<p class="w3-text-blue">Rp. 23.000</p><br>

<h5>Mie Petir</h5>
<p class="w3-text-grey">dengan topping ayam cincang dan kornet</p>
<p class="w3-text-blue">Rp. 17.000</p><br>
</div>

<div id="Minuman" class="w3-container menu w3-padding-48 w3-card">
<h5>Coffee Based</h5>
<p class="w3-text-grey">Ekspresso</p>
<p class="w3-text-blue">Rp. 7.000</p>
<p class="w3-text-grey">Americano</p>
<p class="w3-text-blue">Rp. 10.000</p>
<br>

<h5>Milk Based</h5>
<p class="w3-text-grey">Chocolate/Tiramisu/Red Velvet/Matcha/Taro</p>
<p class="w3-text-blue">Rp. 18.000</p>
<br>

<h5>Tea</h5>
<p class="w3-text-grey">Original Tea</p>
<p class="w3-text-blue">Rp. 9.000</p>
<p class="w3-text-grey">Lemon Tea/Lychee Tea/Choco Tea</p>
<p class="w3-text-blue">Rp. 13.000</p>
<br>

<h5>Soda</h5>
<p class="w3-text-grey">Cola/Sprite/Fanta/</p>
<p class="w3-text-blue">Rp. 20.000</p>
</div> 
<img src="https://i.pinimg.com/originals/8a/f1/96/8af196799d7e799d6361b82f4796f15d.jpg" style="width:100%;max-width:1000px;margin-top:32px;">
</div>
</div>

<!-- Contact/Area Container -->
<div class="w3-container" id="where" style="padding-bottom:32px;">
<div class="w3-content" style="max-width:700px">
<h5 class="w3-center w3-padding-48"><span class="w3-tag w3-wide">Tempat Cafe PINKA</span></h5>
<p>Cafe kita terletak bersebelahan langsung dengan pantai, sehingga bisa melihat sunset yang indah.</p>
<img src="https://i.pinimg.com/originals/cd/b4/c1/cdb4c1b018160b86a5744d76e3bf6bde.jpg" class="w3-image" style="width:100%">
<p><span class="w3-tag">INPONE!</span> Kami juga melayani catering berbagai macam masakan untuk acara besar ataupun kecil. Jika kalian membutuhkan bisa mengisi data dibawah ini:</p>
<form action="/action_page.php" target="_blank">
<p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Nama" required name="Name"></p>
<p><input class="w3-input w3-padding-16 w3-border" type="number" placeholder="Berapa Porsi" required name="People"></p>
<p><input class="w3-input w3-padding-16 w3-border" type="datetime-local" placeholder="Waktu dan Tempat" required name="date" value="2023-10-02T20:00"></p>
<p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Request" required name="Message"></p>
<p><button class="w3-button w3-black" type="submit">KIRIM</button></p>
</form>
</div>
</div>

<!-- End page content -->
</div>

<!-- Footer -->
<footer class="w3-center w3-light-grey w3-padding-48 w3-large">
<p>Powered by <a href="https://www.w3schools.com/w3css/default.asp" title="W3.CSS" target="_blank" class="w3-hover-text-green">w3.css</a></p>
</footer>

<script>
// Tabbed Menu
function openMenu(evt, menuName) {
var i, x, tablinks;
x = document.getElementsByClassName("menu");
for (i = 0; i < x.length; i++) {
x[i].style.display = "none";
}
tablinks = document.getElementsByClassName("tablink");
for (i = 0; i < x.length; i++) {
tablinks[i].className = tablinks[i].className.replace(" w3-dark-grey", "");
}
document.getElementById(menuName).style.display = "block";
evt.currentTarget.firstElementChild.className += " w3-dark-grey";
}
document.getElementById("myLink").click();
</script>

</body>
</html>
