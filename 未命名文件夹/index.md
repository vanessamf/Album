---
title: photos
date: 2019-03-19 11:18:18
type: photos
---
<link rel="stylesheet" href="ins.css">
<link rel="stylesheet" href="photoswipe.css"> 
<link rel="stylesheet" href="default-skin.css"> 
<div class="photos-btn-wrap">
  <a class="photos-btn active" href="javascript:void(0)" target="_blank" rel="external">Photos</a>
</div>
<div class="instagram itemscope">
  <a href="https://vanessamf.github.io" target="_blank" class="open-ins">图片正在加载中…</a>
</div>
 
<script>
  (function() {
    var loadScript = function(path) {
      var $script = document.createElement('script')
      document.getElementsByTagName('body')[0].appendChild($script)
      $script.setAttribute('src', path)
    }
    setTimeout(function() {
        loadScript('ins.js')
    }, 0)
  })()
</script>