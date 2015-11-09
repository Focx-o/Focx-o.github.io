---
layout: default
title: Search Page
---

<h1>Search Page</h1>
<hr/>

<form id="site_search" method="get" action="index.html">
<label for="search_box">Search</label><input type="text" id="search_box" name="query">
<input type="submit" value="search">
</form>

<div id="search_results">
    </div>

<script src="{{ site.BASE_PATH }}js/libs/jquery-1.6.2.min.js"></script>
<script src="{{ site.BASE_PATH }}js/tapir/jquery-tapir.js"></script>
<script>
$('#search_results').tapir({'token': '563f87ce3093adf1ee000000'});
</script>
