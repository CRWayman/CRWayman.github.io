---
layout: post
title: "Arsenal Goal and Assist Contribution Sankey"
date: 2024-04-05
---

<script src="https://code.jquery.com/jquery-3.3.1.min.js"></script>

## Distribution of G/A Contribution from Arsenal Players

<script type="text/javascript">
$(document).ready(function(e) {
    $('#header').load('html/test_sankey.html',function(){alert('loaded')});
});
</script>

<iframe id="igraph" scrolling="no" style="border:none" seamless="seamless" src="html/test_sankey.html"></iframe>
