---
layout: page
title: "Τοποθεσία / Location"
description: "Στην Ανατολικής Θράκης 49, Τούμπα Θεσσαλονίκης – εύκολη πρόσβαση με ΜΜΜ και στάθμευση."
permalink: /location/
---

<link rel="stylesheet" href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css" integrity="sha256-u6Q6S8gPC1LkL5cUAGfDkF0p0pTBK5fE1I1r3hYv+hA=" crossorigin="" />
<script src="https://unpkg.com/leaflet@1.9.4/dist/leaflet.js" integrity="sha256-o9N1j8Mk3xjVtGa3aVdQ0iXLqglpWw2D6I1egYQ3p3s=" crossorigin=""></script>

<div class="section-card map-wrap" id="map" aria-label="Χάρτης σχολής"></div>
<script>
  document.addEventListener("DOMContentLoaded", function () {
    var map = L.map("map").setView([40.6154, 22.9720], 15);
    L.tileLayer("https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png", {
      maxZoom: 19,
      attribution: "© OpenStreetMap contributors"
    }).addTo(map);
    L.marker([40.6154, 22.9720]).addTo(map)
      .bindPopup("Σχολή Οδηγών Καραθανάσης / Karathanasis Driving School")
      .openPopup();
  });
</script>

## Ελληνικά {#el}

### Πώς θα μας βρείτε
- Διεύθυνση: Ανατολικής Θράκης 49, Τούμπα, Θεσσαλονίκη.
- Περιοχή: Κοντά σε κεντρικές στάσεις ΜΜΜ και εύκολη πρόσβαση από την Λαμπράκη.

### Μετακίνηση & στάθμευση
- Συγκοινωνία: Γραμμές λεωφορείου προς Τούμπα σταματούν σε 3-5 λεπτά περπάτημα.
- Στάθμευση: Διαθέσιμος γύρω δρόμος και κάθετες οδοί για σύντομη στάση.
- Προγραμματίστε το ραντεβού σας πριν έρθετε για να σας περιμένουμε.

## English {#en}

### How to find us
- Address: Anatolikis Thrakis 49, Toumpa, Thessaloniki.
- Area: Close to main bus stops with easy access from Lambraki Avenue.

### Transport & parking
- Public transport: Bus lines to Toumpa drop you within a 3–5 minute walk.
- Parking: Street parking available on the surrounding roads and side streets.
- Book your slot so we can welcome you when you arrive.
