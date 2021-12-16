var map;
var marker = [];
var infoWindow = [];
var markerData = [ // マーカーを立てる場所名・緯度・経度
  {
       name: '富士山<br><a href="https://www.google.com/maps/place/%E5%AF%8C%E5%A3%AB%E5%B1%B1/@35.360141,138.718555,14.83z/data=!4m5!3m4!1s0x6019629a42fdc899:0xa6a1fcc916f3a4df!8m2!3d35.3606255!4d138.7273634?hl=ja">googleマップで開く</a>',
       lat: 35.3439,
        lng: 138.7339,
        icon: 'https://1.bp.blogspot.com/-tVeC6En4e_E/X96mhDTzJNI/AAAAAAABdBo/jlD_jvZvMuk3qUcNjA_XORrA4w3lhPkdQCNcBGAsYHQ/s100/onepiece01_luffy.png' // TAM 東京のマーカーだけイメージを変更する
 }, {
        name: '広島県立美術館です。はい。',
     lat: 34.399803,
        lng: 132.465544
 }, {
        name: '特に何もない道路<br><a href="https://www.amazon.co.jp/">特に何もないからAmazonへ</a>',
     lat: 35.106426,
      lng: 136.373496
 },
];
 
function initMap() {
 // 地図の作成
    var mapLatLng = new google.maps.LatLng({lat: markerData[0]['lat'], lng: markerData[0]['lng']}); // 緯度経度のデータ作成
   map = new google.maps.Map(document.getElementById('sample'), { // #sampleに地図を埋め込む
     center: mapLatLng, // 地図の中心を指定
      zoom: 6 // 地図のズームを指定
   });
 
 // マーカー毎の処理
 for (var i = 0; i < markerData.length; i++) {
        markerLatLng = new google.maps.LatLng({lat: markerData[i]['lat'], lng: markerData[i]['lng']}); // 緯度経度のデータ作成
        marker[i] = new google.maps.Marker({ // マーカーの追加
         position: markerLatLng, // マーカーを立てる位置を指定
            map: map // マーカーを立てる地図を指定
       });
 
     infoWindow[i] = new google.maps.InfoWindow({ // 吹き出しの追加
         content: '<div class="sample">' + markerData[i]['name'] + '</div>' // 吹き出しに表示する内容
       });
 
     markerEvent(i); // マーカーにクリックイベントを追加
 }
 
   marker[0].setOptions({// オプション設定
        icon: {
         url: markerData[0]['icon']// マーカーの画像を変更
       }
   });
}
 
// マーカーにクリックイベントを追加
function markerEvent(i) {
    marker[i].addListener('click', function() { // マーカーをクリックしたとき
      infoWindow[i].open(map, marker[i]); // 吹き出しの表示
  });
}
