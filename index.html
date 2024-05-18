<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="utf-8">
  <meta content="width=device-width, initial-scale=1.0" name="viewport">

  <title>Groovin Bootstrap Template - Index</title>
  <meta content="" name="description">
  <meta content="" name="keywords">


 <!-- Google Fonts -->
 <link href="https://fonts.googleapis.com/css?family=Open+Sans:300,300i,400,400i,600,600i,700,700i|Roboto:300,300i,400,400i,500,500i,600,600i,700,700i|Poppins:300,300i,400,400i,500,500i,600,600i,700,700i" rel="stylesheet">

 <!-- Vendor CSS Files -->
 <link href="assets/vendor/animate.css/animate.min.css" rel="stylesheet">
 <link href="assets/vendor/bootstrap/css/bootstrap.min.css" rel="stylesheet">
 <link href="assets/vendor/bootstrap-icons/bootstrap-icons.css" rel="stylesheet">
 <link href="assets/vendor/boxicons/css/boxicons.min.css" rel="stylesheet">
 <link href="assets/vendor/glightbox/css/glightbox.min.css" rel="stylesheet">
 <link href="assets/vendor/swiper/swiper-bundle.min.css" rel="stylesheet">

 <!-- Template Main CSS File -->
 <link href="assets/css/style.css" rel="stylesheet">
 <link href="Lib/ol/ol.css" rel="stylesheet">
 <style>
    .map {
      width: 100%;
      height:500px;
    }
    .boxTool{
     z-index: 0;
     position:absolute;
    }
  </style>
</head>

<body>

  <!-- ======= Header ======= -->
  <header id="header" class="d-flex align-items-center">
    <div class="container d-flex align-items-center justify-content-between">

      <h1 class="logo"><a href="index.html"><img src="images/uniska-bjm.png"> Perkuliahan GIS</a></h1>
      <!-- Uncomment below if you prefer to use an image logo -->
      <!-- <a href="index.html" class="logo"><img src="assets/img/logo.png" alt="" class="img-fluid"></a>-->

      <nav id="navbar" class="navbar">
        <ul>
          <li><a class="nav-link scrollto active" href="#hero">Home</a></li>
          <li><a class="nav-link scrollto" href="#about">About</a></li>
          <li><a class="nav-link scrollto" href="#services">Services</a></li>
          
        </ul>
        <i class="bi bi-list mobile-nav-toggle"></i>
      </nav><!-- .navbar -->

    </div>
  </header><!-- End Header -->
 <!-- ======= Hero Section ======= -->
 <main id="main"></main>
    <div class="hero-container">
        <!-- Map -->
        <div id="map" class="map"></div>
        <!-- Menu -->
        <div id="MenuMap" class="boxTool" style="bottom: 10px;">
            <button type="button" class="btn btn-outline-success" title="Basemap"><i class="bi bi-globe bi-x2"></i></button>
            <button type="button" class="btn btn-outline-success" title="Layers"><i class="bi bi-layers"></i></button>
            <button type="button" class="btn btn-outline-success" title="Pengukuran"><i class="bi bi-rulers"></i></button>
        </div>
        <!-- Basemap -->
        <div class="boxTool card col-5" id="BoxBasemap">
          <div class="card-header" id="BoxBasemapheader">
            Basemaps
          </div>
          <div class="card-body row" id="Basemaps">
                    
          </div>
        </div>
        
    </div>

</main><!-- End #main -->    

  <a href="#" class="back-to-top d-flex align-items-center justify-content-center"><i class="bi bi-arrow-up-short"></i></a>
<script src="Lib/ol/ol.js"></script>
<script src="js/dragmove.js"></script>
<script src="js/jquery-3.6.0.min.js"></script>
<script>
// pengaturan posisi  
document.getElementById("map").style.height = screen.height -200 + "px";
document.getElementById("MenuMap").style.left = screen.width/2 - 100 + "px";
document.getElementById("BoxBasemap").style.left = screen.width/2 - 300 + "px";
document.getElementById("BoxBasemap").style.top = screen.height/2 -200 + "px";

//mengaktifkan mode move
dragElement(document.getElementById("BoxBasemap"));

//global variabel
var Basemap;

Basemap = new ol.layer.Tile({
      source: new ol.source.OSM(),
      nama : "Basemap"
    })

var map = new ol.Map({
  layers: [Basemap],
  target: 'map',
  view: new ol.View({
    center: ol.proj.fromLonLat([120.84404, -2.433331]),
    zoom: 5,
  }),
});

function UpdateBaseMap(u,t,p){
  if(t== "ESRI"){
    var NewBaseMap = new ol.source.TileArcGISRest({
      url : u,
      attributions  : ['Open Layer, Esri, Hidayatul Rahman']
    });
    Basemap.setSource(NewBaseMap); 
  }else{
    var NewBaseMap = new ol.source.TileWMS({
      url : u,
      params : {LAYERS :p, VERSION : '1.1.1'}
    });
    Basemap.setSource(NewBaseMap);
  }
}
</script> 
 
<!-- Basemap JS function -->
<script>
function LoadBasemap(){
  $.ajax({
    url : "datas/basemap.json",
    async : false,
    success : function(data){
      for (i=0; i<data.length; i++){
        var u = "'"+data[i]["url"]+"'";
        var t = "'"+data[i]["type"]+"'";
        var p = "'"+data[i]["param"]+"'";
        var BsMapHTML = '<div class="card" style="width: 10rem;" onclick="UpdateBaseMap('+u+','+t+','+p+')"><img class="card-img-top" src="images/basemaps/'+data[i]["thumimg"]+'" alt="'+data[i]["nama"]+'"> <small class="card-title">'+data[i]["nama"]+'</small> </div></div>';
        document.getElementById("Basemaps").innerHTML = BsMapHTML + document.getElementById("Basemaps").innerHTML;
      }
    }
  })
};
LoadBasemap();
</script>

  <!-- Vendor JS Files -->
  <script src="assets/vendor/bootstrap/js/bootstrap.bundle.min.js"></script>
  <script src="assets/vendor/glightbox/js/glightbox.min.js"></script>
  <script src="assets/vendor/isotope-layout/isotope.pkgd.min.js"></script>
  <script src="assets/vendor/php-email-form/validate.js"></script>
  <script src="assets/vendor/purecounter/purecounter.js"></script>
  <script src="assets/vendor/swiper/swiper-bundle.min.js"></script>

  <!-- Template Main JS File -->
  <script src="assets/js/main.js"></script>

</body>

</html>