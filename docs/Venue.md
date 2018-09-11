---
layout: page
title: Location
permalink: /venue/
---

The workshop will be held in the King's building (at the Strand Campus) of King's College London, which is located in central London (see the map below). All talks will be given in the Nash Lecture theatre, whilst registration, lunch and poster sessions will take place in the River room.

<p><em>If you are not based at King's College London you may have to register as a visitor when you arrive. Please factor this into your travel arrangements.</em></p>

<p> If you are travelling by public transport the Strand Campus can easily be reached using the London Underground network. The closest Underground Stations include:

 <li>Temple (Circle and District lines) - 2 minutes walk</li>
  <li>Charing Cross (Bakerloo and Northern lines) - 10 minutes walk</li>
  <li>Embankment (Circle, District and Bakerloo lines) - 10 minutes walk</li>
  <li>Waterloo (Jubilee, Northern, Bakerloo, Waterloo & City lines) - 12 minutes walk</li>
  <li>Holborn (Central and Picadilly lines) - 12 minutes walk</li>
  
<p><p> Charing Cross, Waterloo and Blackfriars National Rail stations are all also within 10 minutes walking distance.

<p>
<p>
<p>

<div id="map" style="width:100%;height:500px"></div>

<script>
function myMap() {
  var myCenter = new google.maps.LatLng(51.5115, -0.1160);
  var mapCanvas = document.getElementById("map");
  var mapOptions = {center: myCenter, zoom: 15};
  var map = new google.maps.Map(mapCanvas, mapOptions);
  var marker = new google.maps.Marker({position:myCenter});
  marker.setMap(map);

  // Zoom to 9 when clicking on marker
  google.maps.event.addListener(marker,'click',function() {
    map.setZoom(9);
    map.setCenter(marker.getPosition());
  });
}
</script>

<script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyAnbIPAAR4AnMPifUphNRnNMHJ3Go4CF54&callback=myMap"></script>
<!--
To use this code on your website, get a free API key from Google.
Read more at: https://www.w3schools.com/graphics/google_maps_basic.asp
-->



