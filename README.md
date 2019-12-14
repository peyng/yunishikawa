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
  background:url(https://torokoid.github.io/fts_furuhashi/20181115_29.JPG) center/cover no-repeat; /*fixedをトル！*/
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
	
<h1><span class="blue"><strong>簡易、支払い＆精算計算</strong></span></h1>


        
<section>

<ul>
<li> <input type="button" id="btn1" value="精算計算  " onclick="btn1Click();" /> 　←　支払い＆精算計算、開始ボタン</li>
</ul>
    
<script>  
//ボタン１をクリックした時の処理
function btn1Click(){ 

    var selects = prompt('参加人数を入力！');

    var selectss = prompt('支払った人の人数を入力！');

    var koukin = prompt('繰り越し金額を入力！');
    
var nama = [];
    for (var i=0; i<selectss; i++){
      nama[i] = prompt("支払った人の名前を入力");
    }   

var menu = [];    
    for (var i=0; i<selectss; i++){
      menu[i] = prompt(nama[i] + "さんの支払金額を入力");
    } 

document.write("各自の支払金額は<br>")
    for (var i=0; i<menu.length; i++){
      document.write(nama[i] + "さん：" + menu[i] + "円 <br>")
    }
    
//各自の会計額を計算
    
var kasann = [];
      kasann[0] = menu[0];
    for (var i=0; i<selectss-1; i++){
kasann[i+1] = Math.round (Number(kasann[i]) + Number(menu[i+1]));
      }
    
var kasan = Math.round (Number(kasann[i]) - Number(koukin))
      
//各自の分担分を計算

var buntan = Math.round (Number(kasan)/Number(selects));

//各自の割り勘分を計算

var wari = [];
    for (var i=0; i<selects; i++){
    wari[i] = Math.round (Number(menu[i]) - Number(buntan));
      }

var kasann = kasann[selectss-1]
    
document.write("<br>経費の総額：" + kasann + "円<br>")
      
document.write("公金補助額：" + koukin + "円<br>")

document.write("精算金額の総額：" + kasan + "円<br>")
      
document.write("一人当たりの分担：" + buntan + "円<br>")

document.write("<br>支払った人への払い戻し金額は<br>")
    for (var i=0; i<menu.length; i++){
      document.write(nama[i] + "さん：" + wari[i] + "円 <br>")
    }

document.write ("<br>以上、お帰りも気を付けて、次回も元気に再会～(^^)/"); 
    
        document.bgColor = "#00ff80";
        document.fgColor = "blue";
    
}

    </script>
    
        </section>
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
<!-- フッタ -->
 <footer>
 Copyright 2019/12/03 S.Hada
 </footer>

<h1><span class="yellow"><marquee behavior="alternate">!!! 2019年12月14日(土)〜１５日（日）　!!!</marquee></span></h1>
<p align="right"><marquee direction="right" scrollamount="20" width="30%">(^_^)/~hada</marquee></p>
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
<div>
<h3><span class="white">↓ 画像はクリックで拡大します。スライドショーで閲覧できます。</span></h3>
<a href="20181115_02.JPG" data-lightbox="abc"><img src="20181115_02.JPG" alt="サンプル画像" width="180" /></a>
<a href="20181115_03.JPG" data-lightbox="abc"><img src="20181115_03.JPG" alt="サンプル画像" width="180" /></a>
<a href="20181115_04.JPG" data-lightbox="abc"><img src="20181115_04.JPG" alt="サンプル画像" width="180" /></a>
<a href="20181115_05.JPG" data-lightbox="abc"><img src="20181115_05.JPG" alt="サンプル画像" width="180" /></a>
<a href="20181115_06.JPG" data-lightbox="abc"><img src="20181115_06.JPG" alt="サンプル画像" width="180" /></a>
<a href="20181115_07.JPG" data-lightbox="abc"><img src="20181115_07.JPG" alt="サンプル画像" width="180" /></a>
<a href="20181115_08.JPG" data-lightbox="abc"><img src="20181115_08.JPG" alt="サンプル画像" width="180" /></a>
<a href="20181115_09.JPG" data-lightbox="abc"><img src="20181115_09.JPG" alt="サンプル画像" width="100" /></a>
<a href="20181115_10.JPG" data-lightbox="abc"><img src="20181115_10.JPG" alt="サンプル画像" width="100" /></a>
<a href="20181115_11.JPG" data-lightbox="abc"><img src="20181115_11.JPG" alt="サンプル画像" width="100" /></a>
<a href="20181115_12.JPG" data-lightbox="abc"><img src="20181115_12.JPG" alt="サンプル画像" width="180" /></a>
<a href="20181115_13.JPG" data-lightbox="abc"><img src="20181115_13.JPG" alt="サンプル画像" width="180" /></a>
<a href="20181115_14.JPG" data-lightbox="abc"><img src="20181115_14.JPG" alt="サンプル画像" width="180" /></a>
<a href="20181115_15.JPG" data-lightbox="abc"><img src="20181115_15.JPG" alt="サンプル画像" width="180" /></a>
<a href="20181115_16.JPG" data-lightbox="abc"><img src="20181115_16.JPG" alt="サンプル画像" width="180" /></a>
<a href="20181115_17.JPG" data-lightbox="abc"><img src="20181115_17.JPG" alt="サンプル画像" width="180" /></a>
<a href="20181115_18.JPG" data-lightbox="abc"><img src="20181115_18.JPG" alt="サンプル画像" width="180" /></a>
<a href="20181115_19.JPG" data-lightbox="abc"><img src="20181115_19.JPG" alt="サンプル画像" width="180" /></a>
<a href="20181115_20.JPG" data-lightbox="abc"><img src="20181115_20.JPG" alt="サンプル画像" width="180" /></a>
<a href="20181115_21.JPG" data-lightbox="abc"><img src="20181115_21.JPG" alt="サンプル画像" width="100" /></a>
<a href="20181115_22.JPG" data-lightbox="abc"><img src="20181115_22.JPG" alt="サンプル画像" width="180" /></a>
<a href="20181115_23.JPG" data-lightbox="abc"><img src="20181115_23.JPG" alt="サンプル画像" width="180" /></a>
<a href="20181115_24.JPG" data-lightbox="abc"><img src="20181115_24.JPG" alt="サンプル画像" width="100" /></a>
<a href="20181115_25.JPG" data-lightbox="abc"><img src="20181115_25.JPG" alt="サンプル画像" width="180" /></a>
<a href="20181115_26.JPG" data-lightbox="abc"><img src="20181115_26.JPG" alt="サンプル画像" width="180" /></a>
<a href="20181115_27.JPG" data-lightbox="abc"><img src="20181115_27.JPG" alt="サンプル画像" width="180" /></a>
<a href="20181115_28.JPG" data-lightbox="abc"><img src="20181115_28.JPG" alt="サンプル画像" width="360" /></a>
<a href="20181115_29.JPG" data-lightbox="abc"><img src="20181115_29.JPG" alt="サンプル画像" width="540" /></a>
<a href="20181115_30.JPG" data-lightbox="abc"><img src="20181115_30.JPG" alt="サンプル画像" width="90" /></a>
<a href="20181115_31.JPG" data-lightbox="abc"><img src="20181115_31.JPG" alt="サンプル画像" width="90" /></a>
<h4><span class="white">↑パノラマ・マジックで、少し歪んじゃった人が居たりしますが、ご愛敬〜〜(^_^)v。</span></h4><br>
<h4><span class="white">ここからは加藤さん撮影分。</span></h4><br>
<a href="20181115_32.JPG" data-lightbox="abc"><img src="20181115_32.JPG" alt="サンプル画像" width="180" /></a>
<a href="20181115_33.JPG" data-lightbox="abc"><img src="20181115_33.JPG" alt="サンプル画像" width="100" /></a>
<a href="20181115_34.JPG" data-lightbox="abc"><img src="20181115_34.JPG" alt="サンプル画像" width="100" /></a>
<a href="20181115_35.JPG" data-lightbox="abc"><img src="20181115_35.JPG" alt="サンプル画像" width="100" /></a>
<a href="20181115_36.JPG" data-lightbox="abc"><img src="20181115_36.JPG" alt="サンプル画像" width="100" /></a>
<a href="20181115_37.JPG" data-lightbox="abc"><img src="20181115_37.JPG" alt="サンプル画像" width="180" /></a>
<a href="20181115_38.JPG" data-lightbox="abc"><img src="20181115_38.JPG" alt="サンプル画像" width="180" /></a>
<a href="20181115_39.JPG" data-lightbox="abc"><img src="20181115_39.JPG" alt="サンプル画像" width="100" /></a>
<a href="20181115_40.JPG" data-lightbox="abc"><img src="20181115_40.JPG" alt="サンプル画像" width="100" /></a>
<a href="20181115_41.JPG" data-lightbox="abc"><img src="20181115_41.JPG" alt="サンプル画像" width="100" /></a>
<a href="20181115_42.JPG" data-lightbox="abc"><img src="20181115_42.JPG" alt="サンプル画像" width="100" /></a>
<a href="20181115_43.JPG" data-lightbox="abc"><img src="20181115_43.JPG" alt="サンプル画像" width="180" /></a>
<a href="20181115_44.JPG" data-lightbox="abc"><img src="20181115_44.JPG" alt="サンプル画像" width="100" /></a>
<a href="20181115_45.JPG" data-lightbox="abc"><img src="20181115_45.JPG" alt="サンプル画像" width="100" /></a>
<a href="20181115_46.JPG" data-lightbox="abc"><img src="20181115_46.JPG" alt="サンプル画像" width="180" /></a>
<a href="20181115_47.JPG" data-lightbox="abc"><img src="20181115_47.JPG" alt="サンプル画像" width="100" /></a>

<h4><span class="white">ここからは雅代さん撮影分。</span></h4><br>
<a href="20181115_48.JPG" data-lightbox="abc"><img src="20181115_48.JPG" alt="サンプル画像" width="180" /></a>
<a href="20181115_51.JPG" data-lightbox="abc"><img src="20181115_51.JPG" alt="サンプル画像" width="180" /></a>
<a href="20181115_52.JPG" data-lightbox="abc"><img src="20181115_52.JPG" alt="サンプル画像" width="180" /></a>
<a href="20181115_53.JPG" data-lightbox="abc"><img src="20181115_53.JPG" alt="サンプル画像" width="180" /></a>
<a href="20181115_54.JPG" data-lightbox="abc"><img src="20181115_54.JPG" alt="サンプル画像" width="180" /></a>
<a href="20181115_55.JPG" data-lightbox="abc"><img src="20181115_55.JPG" alt="サンプル画像" width="180" /></a>
<a href="20181115_59.JPG" data-lightbox="abc"><img src="20181115_59.JPG" alt="サンプル画像" width="180" /></a>
<a href="20181115_60.JPG" data-lightbox="abc"><img src="20181115_60.JPG" alt="サンプル画像" width="180" /></a>
<br>
<a href="20181115_49.JPG" data-lightbox="abc"><img src="20181115_49.JPG" alt="サンプル画像" width="100" /></a>
<a href="20181115_50.JPG" data-lightbox="abc"><img src="20181115_50.JPG" alt="サンプル画像" width="100" /></a>
<a href="20181115_56.JPG" data-lightbox="abc"><img src="20181115_56.JPG" alt="サンプル画像" width="100" /></a>
<a href="20181115_57.JPG" data-lightbox="abc"><img src="20181115_57.JPG" alt="サンプル画像" width="100" /></a>
<a href="20181115_58.JPG" data-lightbox="abc"><img src="20181115_58.JPG" alt="サンプル画像" width="100" /></a>

</div>



<br><br><br>

みなさま<br>

手持ちの写真でHPを暫定構成してみました。<br>

https://peyng.github.io/yunishikawa/<br>

お手元の写真を共有いただければ、HPに追加しますので、ご連絡下さい。<br>

羽田<br></span>
</main>
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
