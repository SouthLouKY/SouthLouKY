---
layout: default
permalink: /
---

<link rel="shortcut icon" type="image/x-icon" href="{{ "/images/favicon.ico" | prepend: site.baseurl }}" >

{% include landing.html %}

<script>
document.addEventListener("DOMContentLoaded", function() {
    var attribution = document.getElementById("attribution");
    if (attribution) {
        attribution.style.display = "none";
    }
});    
</script>
