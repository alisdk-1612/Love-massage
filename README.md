<html><meta charset='UTF-8'/><meta content='width=device-width, initial-scale=1, user-scalable=1, minimum-scale=1, maximum-scale=5' name='viewport'/><meta content='IE=edge' http-equiv='X-UA-Compatible'/>
<link rel="preconnect" href="https://fonts.googleapis.com"><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin><link href="https://fonts.googleapis.com/css2?family=Quicksand&display=swap" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/npm/sweetalert2@11.0.19/dist/sweetalert2.all.min.js"></script>
 
<head>
<!-- 
  Made with love by Ali!

     From: Ali Sadikin
     To : Pacar Aku
     

  Thanks to you <3
-->
</head>

<body>
<style>
body{background-image:url("https://i.postimg.cc/RCXKky2z/IMG-20211205-131524-095.jpg");background-repeat: no-repeat;animation:none;background-size: 100% 100%;}
@keyframes fanim {0% {background-size: 100% 100%;}25% {background-size: 103% 103%;} 50% {background-size: 105% 105%;} 75% {background-size: 103% 103%;} 100% {background-size: 100% 100%;}}
a{text-decoration:none;} body{font-family: 'Quicksand', sans-serif;padding: 5px 25px} body::before{content:"\00A9  linkr.bio/rayyarr";color:white;opacity:.2;font-size:5px;position:absolute;bottom:25px;left:calc(50vw - 22px);}

#Content{opacity:0;transition:all 1s ease;}
#pergeseran{margin-top:70px;opacity:0;visibility:hidden;transition:all 1s ease;display:flex;flex-wrap:nowrap;align-items:flex-start;justify-content:flex-start;position:relative;width:calc(100%);left:-20px;padding:0 20px; overflow-y:hidden;overflow-x:scroll;scroll-behavior:smooth;scroll-snap-type:x mandatory; -ms-overflow-style:none;-webkit-overflow-scrolling:touch}
#pergeseran > *{padding:8px;display:flex;flex-wrap:nowrap;text-align:center;font-size:15px;font-weight:700;align-items:center;justify-content:center;border-radius:5px;flex-shrink:0; width:90%; min-height:80px;margin:0 15px 0 0; scroll-snap-align:center} #pergeseran > *:last-child{margin-right:0} #pergeseran:after{content:'';display:block;flex-shrink:0; align-self:stretch;padding-left:20px}
#pergeseran{margin-top:70px;opacity:0;visibility:hidden;transition:all 1s ease;display:flex;flex-wrap:nowrap;align-items:flex-start;justify-content:flex-start;position:relative;max-width:600px;padding:0 20px; overflow-y:hidden;overflow-x:scroll;scroll-behavior:smooth;scroll-snap-type:x mandatory; -ms-overflow-style:none;-webkit-overflow-scrolling:touch}
#pergeseran p{background:#003A76;color:white;border: 0px dashed #fff;border-radius:8px;padding:8px;display:flex;flex-wrap:nowrap;text-align:center;font-size:15px;font-weight:700;align-items:center;justify-content:center;flex-shrink:0; width:90%; min-height:80px;margin:0 15px 0 0; scroll-snap-align:center} #pergeseran > *:last-child{margin-right:0} #pergeseran:after{content:'';display:block;flex-shrink:0; align-self:stretch;padding-left:20px}
#pergeseran p b{display:block;} #pergeseran p b img{width:80px;height:80px;margin:20px 0;}
#pergeseran > *:nth-child(odd){background:#272A49;color:white;} #pergeseran > *:nth-child(even){background:#141626;color:white;}
#tm{color:#FFD700;margin-left:6px}#tm:hover{opacity:.5;}

.foto{display:block;text-align:center;width:100%;height:100px;margin-top:50px;}
.foto > *{display:flex;align-items:center;justify-content:center;margin-top:15px;font-weight:700;font-size:18px;text-shadow: 0px 2px 2px rgba(0, 0, 0, .8);color:white}
.foto img{background:#fff;padding:3px;border-radius:5%;transition:all .1s ease;}
.swal2-modal{top:-60px}
.adB{min-height:45px;display:flex;align-items:center;justify-content:center;font-size:15px;font-weight:700;color:#565656;} .adB::before{content:attr(data-text)} a{text-decoration:none;}
  .sticky-ad {
            display: -webkit-box;
            display: -ms-flexbox;
            display: flex;
            -webkit-box-orient: vertical;
            -webkit-box-direction: normal;
            -ms-flex-direction: column;
            flex-direction: column;
            -webkit-box-align: center;
            -ms-flex-align: center;
            align-items: center;
            -webkit-box-pack: center;
            -ms-flex-pack: center;
            justify-content: center;
            overflow: visible;
            position: fixed;
            text-align: center;
            bottom: -130px;
            left: 0;
            width: 100%;
            z-index: 999;
            max-height: 104px;
            background-image: none;
            background-color: #fff;
            box-shadow: 0 0 5px 0 rgba(0, 0, 0, 0.2);
            margin-bottom: 0;
            padding-top: 4px;
            transition: all 0.4s ease-in-out;
        }
        .sticky-ad-close-button {
            position: absolute;
            width: 28px;
            height: 28px;
            top: -28px;
            right: 0;
            background-image: url("data:image/svg+xml;charset=utf8,%3csvg width='13' height='13' viewBox='341 8 13 13' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'%3e%3cg%3e%3cpath style='fill:%234F4F4F' d='M354 9.31L352.69 8l-5.19 5.19L342.31 8 341 9.31l5.19 5.19-5.19 5.19 1.31 1.31 5.19-5.19 5.19 5.19 1.31-1.31-5.19-5.19z'%3e%3c/path%3e%3c/g%3e%3c/svg%3e");
            background-size: 13px 13px;
            background-position: 9px;
            background-color: #fff;
            background-repeat: no-repeat;
            box-shadow: 0 -1px 1px 0 rgba(0, 0, 0, 0.2);
            border: none;
            border-radius: 12px 0 0 0;
            cursor: pointer;
        }
        .sticky-ad-close-button:before {
            position: absolute;
            content: "";
            top: -20px;
            right: 0;
            left: -20px;
            bottom: 0;
        }
        
</style>

<div id='Content'>
<div class="foto"><div class="image">
<!-- Foto Atas --><img src="https://i.postimg.cc/1tYFjC4j/rain-together.gif" width="100px" height="100px"/></div></div>

<div id='pergeseran'>
<p><i>Geser &#128073;</i></p>
<p>Halo cantikk~</p>
<p>kamu yang semanagat ya magangnya 🥺</p>
<p>Semoga kamu dilancarin kerjaannya🤗</p>
<p>Jangan lupa sholat ya sayangnyaa aku</p>
<p>makann juga jangan lupa,</p>
<p>jangan suka closure pliss haha</p>
<p><i>Okeeyyy?</i></p>
<p>Klik ini dong &#129303; &#128073; <a id="tm" onClick='pmau();'>[ &#128571; ]</a></p>
 </div>
    </div>
    <audio id="audioPlayer" src="v09044g40000cjo88trc77uca7d1nai0.mp4" loop></audio>
    <script>
        function play() {
            var audio = document.getElementById("audioPlayer");
            audio.volume = 50.5; // Atur volume
            audio.play();
        }

        async function start() {
            await Swal.fire('Halo ツ');
            setTimeout(mulai, 900);
            play(); // Memanggil fungsi play
        }
        start();

        async function pmau() {
            await Swal.fire({
                title: 'nyemangatin pacar ><',
                text: 'semoga dilancarin cantik <3',
                imageUrl: 'https://i.postimg.cc/KYM5FfBD/bubududu.gif',
                imageWidth: 120,
                imageHeight: 120,
            });
            await Swal.fire('Kirim pesan ke no WhatsApp aku ya!!!');
            window.location = "https://api.whatsapp.com/send?phone=&text=Makasii yaaa cantik><";
        }
    </script>
<div class='sticky-ad' id='sticky-ad'>
 <div class='adB'><a rel="dofollow" href='https://bit.ly/htmlfeeldream'>Ambil Mentahan Script HTML di Sini!</a></div>
<button aria-label='Close this ad' class='sticky-ad-close-button' onclick='hilangkan();'/>
</div>
<script>
  function tunjukkan(){document.getElementById("sticky-ad").style = "bottom: 0px";}
function hilangkan() {document.getElementById("sticky-ad").style = "bottom: -130px";}
  //Audio Link MP3
  function play() {var audio = new Audio('https://hei.likeadream.repl.co/kopet.mp3');audio.play();audio.loop=true;audio.addEventListener('ended', function() {this.currentTime = 0;this.play();}, false);} const swals = Swal.mixin({cancelButtonColor: '#909090', confirmButtonColor: '#00B487', allowOutsideClick: false,});

async function pmau(){
await swals.fire({
  title: 'love you cantik ><',
  text: 'semoga dilancarin cantik <3',
  imageUrl: 'https://i.postimg.cc/KYM5FfBD/bubududu.gif',
  imageWidth: 120,
  imageHeight: 120,
});
await swals.fire('Kirim pesan ke no WhatsApp aku ya!!!');
window.location = "https://api.whatsapp.com/send?phone=&text=Makasii yaaa cantik><";}

async function start() {await swals.fire('Halo ツ');setTimeout(mulai, 900);play();}
start();
</script>

<script>
  function showDiv() {setTimeout(tunjukkan,5555);document.getElementById('Content').style.opacity = "1";}
  function iloveu() {document.getElementById('sp1').style.display = "none";document.getElementById('sp2').style.display = "block";document.getElementById('text2').style.display = "none";}
  function mulai() {ketiknm();showDiv();document.querySelector("body").style.animation = "none 6s ease infinite";}
  function ketiknm() {document.getElementById('pergeseran').style.opacity = "1";document.getElementById('pergeseran').style.visibility = "visible";document.getElementById('pergeseran').style.margin = "40px 0 0 0";}
</script>
</body>
</html>
