---
permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!-- Image + map -->
<img id="hero-img" src="/images/Conference.png" alt="About" usemap="#mapConf" style="max-width:100%; height:auto; display:block;">

<map name="mapConf">
  <area target="_top" alt="See Research Projects" title="See Research Projects" href="https://lucaspagepereira.github.io/projects/" coords="550,1210,1178,1298" shape="rect">
  <area target="_top" alt="See Publications" title="See Publications" href="https://lucaspagepereira.github.io/publications/" coords="1395,1286,1815,1361" shape="rect">
  <area target="_top" alt="See Teaching" title="See Teaching" href="https://lucaspagepereira.github.io/teaching/" coords="1107,1409,1452,1510" shape="rect">
  <area target="_top" alt="See Research Notebook" title="See Research Notebook" href="https://lucaspagepereira.github.io/posts/" coords="1006,1545,1589,1618" shape="rect">
</map>

<!-- Lib depuis un CDN -->
<script src="/scripts/imageMapResizer.min.js"></script>

<!-- Sécurité : si l’attribut onload ci-dessus était ignoré, on force aussi après le chargement complet -->
<script>
  window.addEventListener('load', function () {
    if (typeof imageMapResize === 'function') imageMapResize();
  });
</script>

<noscript>
  <p>
    <a href="https://lucaspagepereira.github.io/projects/">Projects</a> ·
    <a href="https://lucaspagepereira.github.io/publications/">Publications</a> ·
    <a href="https://lucaspagepereira.github.io/teaching/">Teaching</a> ·
    <a href="https://lucaspagepereira.github.io/posts/">Research Notebook</a>
  </p>
</noscript>
