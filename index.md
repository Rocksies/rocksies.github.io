![alt text](https://github.com/Rocksies/rocksies.github.io/blob/soil-profile/Logo.JPG)

# SSP Geotechnics - Rocksies 

**About:**
<br>
Reimagining geological data and enabling accessibility for the future. 
<br>

**Aims:** 
<br>
1. Creating a space to collate available geotechnical data in Malaysia from SSP S/B. 
2. Having an interactive mapping GUI that can be navigated and searched with geolocation. 
3. Connect available ground profiles via SQL database with a cloud back-end service for constant availability and high reliability. 

<br> 
Last updated: 15th May 2020 
<br> 

<!DOCTYPE html>
<html>
<body>

<h1>My First Google Map</h1>

<div id="googleMap" style="width:100%;height:400px;"></div>

<script>
function myMap() {
var mapProp= {
  center:new google.maps.LatLng(51.508742,-0.120850),
  zoom:5,
};
var map = new google.maps.Map(document.getElementById("googleMap"),mapProp);
}
</script>

<script src="https://maps.googleapis.com/maps/api/js?key=YOUR_KEY&callback=myMap"></script>

</body>
</html>
