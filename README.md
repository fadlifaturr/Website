
<html>
<meta charset='UTF-8'/><meta content='width=device-width, initial-scale=1, user-scalable=1, minimum-scale=1, maximum-scale=5' name='viewport'/><meta content='IE=edge' http-equiv='X-UA-Compatible'/><link rel="preconnect" href="https://fonts.googleapis.com"><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin><link href="https://fonts.googleapis.com/css2?family=Quicksand&display=swap" rel="stylesheet"><script src="https://cdn.jsdelivr.net/npm/sweetalert2@11.0.19/dist/sweetalert2.all.min.js"></script><script src="https://kit.fontawesome.com/4f3ce16e3e.js" crossorigin="anonymous"></script><link href="https://bukadong.likeadream.repl.co/style.css" rel="stylesheet" type="text/css" /><script src="https://bukadong.likeadream.repl.co/script.js"></script>
<head>
<!-- 

</head>
<body>
<style>
body{background-image: url("https://i.postimg.cc/SRHCwxg2/IMG-20211223-114043-063.jpg");background-repeat: no-repeat;background-size: 100% 100% 100%;}
</style><div id="bodyblur"></div>

<div id="konten"><div id="fotoloveu"><div class="image">
<!-- Foto Akhir --><img src="3c8b97f6-e293-419b-add2-ac4d7abdc804.jpg" id="animasi" width="170px" height="170px"/></div><span id="penutup" style="font-size:1.1rem;"></span></div>

<div id="tomAksi"><a class='button' onClick='reaksi();'>Klik Ini!</a></div>

</div>

<!-- Teks, Lagu --><script>
var u=0,penutup;penutup = "I Love You <3";

function play() {//Link Audio Bisa Diganti
var audio = new Audio('https://bukadulu.likeadream.repl.co/Dandelions.mp3');audio.play();}         

//Reaksi
 async function reaksi(){
   await swals.fire('Dah ah:v', 'Sekian aja dulu ya wkwk');
   await swals.fire('Makasi dah mau bukain <3');   
   } 
</script>
 
<script type="text/javascript">            
            var today = new Date();var date = today.getDate()+'/'+(today.getMonth()+1)+'/'+today.getFullYear()+'.';var dateTime = date;
            const swals = Swal.mixin({
                backdrop: 'rgba(0,0,123,0.4)', confirmButtonColor: '#55009E', cancelButtonColor: '#FFCA00', allowOutsideClick: false,
            });
            async function mulai(){
                 await swals.fire({
                  title: 'Pesan untuk kamu', 
                  imageUrl: 'https://i.ibb.co/k1tT78P/your-image.jpg',
                  imageWidth: 150, imageHeight: 150,
                 });   	
                 await swals.fire({
                  title: 'Jangan tidur malem² ya cantik',
                  imageUrl: 'https://i.ibb.co/k1tT78P/your-image.jpg',
                  imageWidth: 120, imageHeight: 120,
                 });
                 await swals.fire({
                  title: 'Jaga kesehatanmu yaa &#129392;',
                  imageUrl: 'https://i.ibb.co/k1tT78P/your-image.jpg',
                  imageWidth: 120, imageHeight: 120,
                 });
                 await swals.fire({
                  title: 'izin ambil photo mu mar wkwk:)noublie pas de rêver de moi! &#129324;',
                  imageUrl: 'https://i.ibb.co/k1tT78P/your-image.jpg',
                  imageWidth: 120, imageHeight: 120,
                 });
                 play();ketik();expl();
            }            
            mulai();
</script>



<!-- Di bawah ini JANGAN DIEDIT SEMBARANGAN -->
<script>
  function tombol() {document.getElementById('tomAksi').style.visibility = "visible";document.getElementById('tomAksi').style.opacity = "1";}
  async function expl(){aksifoto();document.getElementById('bodyblur').style.opacity = "1";document.getElementById('bodyblur').style.visibility = "visible";setTimeout(duar,200);}
  function aksifoto(){var e1 = document.getElementById('animasi');e1.classList.add("degdeg");document.getElementById('fotoloveu').style.opacity = "1";document.getElementById('fotoloveu').style.height = "180px";document.getElementById('fotoloveu').style.margin = "50px 0 0 0";}
  
async function duar(){
document.getElementById('konten').style.top = "0";
document.body.style.backgroundColor = "#000";
}

const body = document.querySelector("body");
function createHeart() {
    const heart = document.createElement("div");
    heart.className = "fas fa-heart";
    heart.style.left = (Math.random() * 90)+"vw";
    heart.style.animationDuration = (Math.random()*3)+2+"s"
    body.appendChild(heart);
}
setInterval(function name(params) {
    var heartArr = document.querySelectorAll(".fa-heart")
    if (heartArr.length > 50) {
       heartArr[0].remove()
    }
},100);

  function ketik() {
    if(u<penutup.length){
      document.getElementById("penutup").innerHTML += penutup.charAt(u);
      u++;
      setTimeout(ketik,110);
    }
    if(u==penutup.length){
    tombol();setInterval(createHeart,300);
    }
  }
</script>
</body>
</html>
