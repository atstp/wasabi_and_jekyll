---
layout: default
---

# async example 2

this fetches the file [`/structure-for-async.wasabi.txt`](/structure-for-async.wasabi.txt)
to build the wasabi document

<script id="wasabi-location">
  (function(){

    var wasabi_file_location = '/structure-for-async.wasabi.txt';

    var this_id = 'wasabi-location';
    var W=window.Wasabi=window.Wasabi||{};W.from=wasabi_file_location;
    W.here=this_id;var s=document.createElement('script');s.src='https://s3'+
    '.amazonaws.com/wasabi.js/get-wasabi.js';document.write(s.outerHTML);
  })();
</script>

