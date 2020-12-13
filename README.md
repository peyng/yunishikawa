# yunishikawa
<html lang="ja">
 <head>
  <meta charset="utf-8" />
	 

<style type="text/css">

  p {
color: #fffafa;
font-size: 1.5em;
 }
<!--
 .red {color:#ff0000;}
 .grey {color:#999999;}
 .snow {color:#fffafa;}
 .yellow {color:#ff0000; background:#ffff00;}
 .blue {color:#0000ff;}
 .white {color:#ffffff; blinking;}
 .waku {border:2px dotted #99cc66;
　　　　　　line-height: 200%;
　　　　　　padding: 10px;}
 -->
	
.date:before{content:"20181115";}
	
	
 #preview{
	position: relative;
	border: 3px solid #333;
	background: #444;
	padding: 5px;
	display: none;
	color: #FFF;
	text-align: center;
}

main {
background-color: rgba(255, 255, 255, 0.3);
}

section {
background-color: rgba(0, 225, 0, 0.5);
}

#wrap {background:none} /*PC用の背景はオフ*/
body::before {
  content:"";
  display:block;
  position:fixed;
  top:0;
  left:0;
  z-index:-1;
  width:100%;
  height:100vh;
  background:url(https://peyng.github.io/yunishikawa/20191214_020.JPG) center/cover no-repeat; /*fixedをトル！*/
  -webkit-background-size:cover;/*Android4*/
  }
 
@media	screen and (min-width: 540px),
	screen and (orientation: landscape) {
   p.note { display: none; }
}
  
</style>

<link href="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.7.1/css/lightbox.css" rel="stylesheet">
 
</head>
<body>
<p class="note">
  モバイル端末をお使いの場合は、画面を横向きにすると
  より見やすくご覧頂けます。
</p>
<!--
<h1><span class="blue"><strong>簡易、支払い＆精算計算</strong></span></h1>


<!--
<section>
<!--
<ul>
<li> <input type="button" id="btn1" value="精算計算  " onclick="btn1Click();" /> 　←　支払い＆精算計算、開始ボタン</li>
</ul>
<!--
<script>  
//ボタン１をクリックした時の処理
function btn1Click(){ 

    var selects = prompt('参加人数を入力！');

    var selectss = prompt('支払った人の人数を入力！');

    var koukin = prompt('繰り越し金額を入力！');
<!--    
var nama = [];
    for (var i=0; i<selectss; i++){
      nama[i] = prompt("支払った人の名前を入力");
    }   
<!--
var menu = [];    
    for (var i=0; i<selectss; i++){
      menu[i] = prompt(nama[i] + "さんの支払金額を入力");
    } 
<!--
document.write("各自の支払金額は<br>")
    for (var i=0; i<menu.length; i++){
      document.write(nama[i] + "さん：" + menu[i] + "円 <br>")
    }
<!--    
//各自の会計額を計算
<!--    
var kasann = [];
      kasann[0] = menu[0];
    for (var i=0; i<selectss-1; i++){
kasann[i+1] = Math.round (Number(kasann[i]) + Number(menu[i+1]));
      }
 <!--   
var kasan = Math.round (Number(kasann[i]) - Number(koukin))
 <!--     
//各自の分担分を計算
<!--
var buntan = Math.round (Number(kasan)/Number(selects));
<!--
//各自の割り勘分を計算
<!--
var wari = [];
    for (var i=0; i<selects; i++){
    wari[i] = Math.round (Number(menu[i]) - Number(buntan));
      }
<!--
var kasann = kasann[selectss-1]
  <!--  
document.write("<br>経費の総額：" + kasann + "円<br>")
  <!--    
document.write("公金補助額：" + koukin + "円<br>")
<!--
document.write("精算金額の総額：" + kasan + "円<br>")
 <!--     
document.write("一人当たりの分担：" + buntan + "円<br>")
<!--
document.write("<br>支払った人への払い戻し金額は<br>")
    for (var i=0; i<menu.length; i++){
      document.write(nama[i] + "さん：" + wari[i] + "円 <br>")
    }
<!--
document.write ("<br>以上、お帰りも気を付けて、次回も元気に再会～(^^)/"); 
    
        document.bgColor = "#00ff80";
        document.fgColor = "blue";
 <!--   
}

    </script>
    
        </section>-->
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

<h1><span class="yellow"><marquee behavior="alternate">!!! 2020年12月12日(土)〜13日(日)@ホテル湯西川 !!!</marquee></span></h1>
<p align="right"><marquee direction="right" scrollamount="20" width="30%">(^_^)/~hada</marquee></p>
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
<div>

<a href="20201212_001.jpg" data-lightbox="abc"><img src="20201212_001.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_002.jpg" data-lightbox="abc"><img src="20201212_002.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_003.jpg" data-lightbox="abc"><img src="20201212_003.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_004.jpg" data-lightbox="abc"><img src="20201212_004.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_005.jpg" data-lightbox="abc"><img src="20201212_005.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_006.jpg" data-lightbox="abc"><img src="20201212_006.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_007.jpg" data-lightbox="abc"><img src="20201212_007.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_008.jpg" data-lightbox="abc"><img src="20201212_008.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_009.jpg" data-lightbox="abc"><img src="20201212_009.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_010.jpg" data-lightbox="abc"><img src="20201212_010.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_011.jpg" data-lightbox="abc"><img src="20201212_011.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_012.jpg" data-lightbox="abc"><img src="20201212_012.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_013.jpg" data-lightbox="abc"><img src="20201212_013.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_014.jpg" data-lightbox="abc"><img src="20201212_014.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_015.jpg" data-lightbox="abc"><img src="20201212_015.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_016.jpg" data-lightbox="abc"><img src="20201212_016.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_017.jpg" data-lightbox="abc"><img src="20201212_017.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_018.jpg" data-lightbox="abc"><img src="20201212_018.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_019.jpg" data-lightbox="abc"><img src="20201212_019.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_020.jpg" data-lightbox="abc"><img src="20201212_020.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_021.jpg" data-lightbox="abc"><img src="20201212_021.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_022.jpg" data-lightbox="abc"><img src="20201212_022.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_023.jpg" data-lightbox="abc"><img src="20201212_023.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_024.jpg" data-lightbox="abc"><img src="20201212_024.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_025.jpg" data-lightbox="abc"><img src="20201212_025.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_026.jpg" data-lightbox="abc"><img src="20201212_026.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_027.jpg" data-lightbox="abc"><img src="20201212_027.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_028.jpg" data-lightbox="abc"><img src="20201212_028.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_029.jpg" data-lightbox="abc"><img src="20201212_029.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_030.jpg" data-lightbox="abc"><img src="20201212_030.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_031.jpg" data-lightbox="abc"><img src="20201212_031.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_032.jpg" data-lightbox="abc"><img src="20201212_032.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_033.jpg" data-lightbox="abc"><img src="20201212_033.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_034.jpg" data-lightbox="abc"><img src="20201212_034.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_035.jpg" data-lightbox="abc"><img src="20201212_035.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_036.jpg" data-lightbox="abc"><img src="20201212_036.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_037.jpg" data-lightbox="abc"><img src="20201212_037.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_038.jpg" data-lightbox="abc"><img src="20201212_038.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_039.jpg" data-lightbox="abc"><img src="20201212_039.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_040.jpg" data-lightbox="abc"><img src="20201212_040.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_041.jpg" data-lightbox="abc"><img src="20201212_041.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_042.jpg" data-lightbox="abc"><img src="20201212_042.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_043.jpg" data-lightbox="abc"><img src="20201212_043.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_044.jpg" data-lightbox="abc"><img src="20201212_044.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_045.jpg" data-lightbox="abc"><img src="20201212_045.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_046.jpg" data-lightbox="abc"><img src="20201212_046.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_047.jpg" data-lightbox="abc"><img src="20201212_047.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_048.jpg" data-lightbox="abc"><img src="20201212_048.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_049.jpg" data-lightbox="abc"><img src="20201212_049.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_050.jpg" data-lightbox="abc"><img src="20201212_050.jpg" alt="サンプル画像" width="200" /></a>
<a href="20201212_051.jpg" data-lightbox="abc"><img src="20201212_051.jpg" alt="サンプル画像" width="200" /></a>


</div>



<h1><span class="yellow"><marquee behavior="alternate">!!! 2019年12月14日(土)〜15日(日)@ホテル湯西川 !!!</marquee></span></h1>
<p align="right"><marquee direction="right" scrollamount="20" width="30%">(^_^)/~hada</marquee></p>
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
<div>
<h3><span class="white">↓ 画像はクリックで拡大します。スライドショーで閲覧できます。</span></h3>

<h2><span class="white">とりあえず、画像を手当たり次第アップしました〜〜(^_^)v。</span></h2><br>


<a href="20191214_002.JPG" data-lightbox="abc"><img src="20191214_002.JPG" alt="サンプル画像" width="900" /></a>
<!--
<a href="20191214_003.JPG" data-lightbox="abc"><img src="20191214_003.JPG" alt="サンプル画像" width="300" /></a>
-->
<a href="20191214_004.JPG" data-lightbox="abc"><img src="20191214_004.JPG" alt="サンプル画像" width="900" /></a>
<a href="20191214_005.JPG" data-lightbox="abc"><img src="20191214_005.JPG" alt="サンプル画像" width="900" /></a>
<a href="20191214_006.JPG" data-lightbox="abc"><img src="20191214_006.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_007.JPG" data-lightbox="abc"><img src="20191214_007.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_008.JPG" data-lightbox="abc"><img src="20191214_008.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_009.JPG" data-lightbox="abc"><img src="20191214_009.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_010.JPG" data-lightbox="abc"><img src="20191214_010.JPG" alt="サンプル画像" width="300" /></a>

<a href="20191214_014.JPG" data-lightbox="abc"><img src="20191214_014.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_015.JPG" data-lightbox="abc"><img src="20191214_015.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_016.JPG" data-lightbox="abc"><img src="20191214_016.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_017.JPG" data-lightbox="abc"><img src="20191214_017.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_018.JPG" data-lightbox="abc"><img src="20191214_018.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_019.JPG" data-lightbox="abc"><img src="20191214_019.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_020.JPG" data-lightbox="abc"><img src="20191214_020.JPG" alt="サンプル画像" width="300" /></a>

<a href="20191214_023.JPG" data-lightbox="abc"><img src="20191214_023.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_024.JPG" data-lightbox="abc"><img src="20191214_024.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_025.JPG" data-lightbox="abc"><img src="20191214_025.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_011.JPG" data-lightbox="abc"><img src="20191214_011.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_012.JPG" data-lightbox="abc"><img src="20191214_012.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_013.JPG" data-lightbox="abc"><img src="20191214_013.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_026.JPG" data-lightbox="abc"><img src="20191214_026.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_027.JPG" data-lightbox="abc"><img src="20191214_027.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_028.JPG" data-lightbox="abc"><img src="20191214_028.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_029.JPG" data-lightbox="abc"><img src="20191214_029.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_030.JPG" data-lightbox="abc"><img src="20191214_030.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_031.JPG" data-lightbox="abc"><img src="20191214_031.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_032.JPG" data-lightbox="abc"><img src="20191214_032.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_033.JPG" data-lightbox="abc"><img src="20191214_033.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_034.JPG" data-lightbox="abc"><img src="20191214_034.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_035.JPG" data-lightbox="abc"><img src="20191214_035.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_036.JPG" data-lightbox="abc"><img src="20191214_036.JPG" alt="サンプル画像" width="300" /></a>
<h2><span class="white">石川さんお勧めの酒屋さんで、ドブロクを買いました。。</span></h2><br>
<a href="20191214_021.JPG" data-lightbox="abc"><img src="20191214_021.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_038.JPG" data-lightbox="abc"><img src="20191214_038.JPG" alt="サンプル画像" width="300" /></a>
<h2><span class="white">道の駅で見つけた、ダムカレー。</span></h2><br>
<a href="20191214_022.JPG" data-lightbox="abc"><img src="20191214_022.JPG" alt="サンプル画像" width="300" /></a>
<h2><span class="white">今回のホテル。</span></h2><br>
<a href="20191214_001.JPG" data-lightbox="abc"><img src="20191214_001.JPG" alt="サンプル画像" width="300" /></a>
<h2><span class="white">Facebook上に見逃していた写真があったので、さらに追記。</span></h2><br>
<a href="20191214_040.JPG" data-lightbox="abc"><img src="20191214_040.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_041.JPG" data-lightbox="abc"><img src="20191214_041.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_042.JPG" data-lightbox="abc"><img src="20191214_042.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_043.JPG" data-lightbox="abc"><img src="20191214_043.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_044.JPG" data-lightbox="abc"><img src="20191214_044.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_045.JPG" data-lightbox="abc"><img src="20191214_045.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_046.JPG" data-lightbox="abc"><img src="20191214_046.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_047.JPG" data-lightbox="abc"><img src="20191214_047.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_048.JPG" data-lightbox="abc"><img src="20191214_048.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_049.JPG" data-lightbox="abc"><img src="20191214_049.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_050.JPG" data-lightbox="abc"><img src="20191214_050.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_051.JPG" data-lightbox="abc"><img src="20191214_051.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_052.JPG" data-lightbox="abc"><img src="20191214_052.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_053.JPG" data-lightbox="abc"><img src="20191214_053.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_054.JPG" data-lightbox="abc"><img src="20191214_054.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_055.JPG" data-lightbox="abc"><img src="20191214_055.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_056.JPG" data-lightbox="abc"><img src="20191214_056.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_057.JPG" data-lightbox="abc"><img src="20191214_057.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_058.JPG" data-lightbox="abc"><img src="20191214_058.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_059.JPG" data-lightbox="abc"><img src="20191214_059.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_060.JPG" data-lightbox="abc"><img src="20191214_060.JPG" alt="サンプル画像" width="300" /></a>
<h2><span class="white">Facebook上の見逃し画像をさらに追記。</span></h2><br>
<a href="20191214_061.JPG" data-lightbox="abc"><img src="20191214_061.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_062.JPG" data-lightbox="abc"><img src="20191214_062.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_063.JPG" data-lightbox="abc"><img src="20191214_063.JPG" alt="サンプル画像" width="300" /></a>
<a href="20191214_064.JPG" data-lightbox="abc"><img src="20191214_064.JPG" alt="サンプル画像" width="300" /></a>

<h2><span class="white">初日夕食、動画リンク</span></h2><br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/Akq6nxiSs4g" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

</div>



<br><br><br>

みなさま<br>

手持ちの写真でHPを暫定構成してみました。<br>

<p align="left"> <img src="QR_yunishikawa.jpg" alt="アクセス用QRコード" width="100">アクセス用QRコード</p>

お手元の写真を共有いただければ、HPに追加しますので、ご連絡下さい。<br>

羽田<br>
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>	
	
	

<script src="https://code.jquery.com/jquery-1.12.4.min.js" type="text/javascript"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.7.1/js/lightbox.min.js" type="text/javascript"></script>


<br><br><br><br><br><br><br><br><br><br><br><br><br><br>

<script type='text/javascript' src='https://torokoid.github.io/shiba/jquery.js?ver=1.12.4'></script>
<script src="https://torokoid.github.io/shiba/jquery.goup.min.js"></script>
<script src="https://torokoid.github.io/shiba/my.js"></script> 

<!-- フッタ -->
 <footer><span class="snow">
 Copyright 2019/12/14 S.Hada
	</span></footer>
