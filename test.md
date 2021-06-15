---
layout: default
title: HODOR-BLOG
description: TEST-2021-6-8
---



```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```
{:#aa}

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```
<!--data-clipboard-text属性的值将会被复制-->
<div id="btn" class="js-copy" data-clipboard-target="#aa">
    <span>点击复制</span>
</div>
 <script src="./clipboard.min.js"></script>
<script>
    var btn = document.getElementById('btn');
    var clipboard = new Clipboard(btn);//实例化

    //复制成功执行的回调，可选
    clipboard.on('success', function(e) {
        alert('复制成功')
    });

    //复制失败执行的回调，可选
    clipboard.on('error', function(e) {
        console.log(e);
    });
</script>
{% if page.content contains "code" %}
<script>
// get all <code> elements
var allCodeBlocksElements = $( "code" );

allCodeBlocksElements.each(function(i) {
  // add different id for each code block

  // target 
  var currentId = "codeblock" + (i + 1);
  $(this).attr('id', currentId);
     
  //trigger
  var clipButton = '<button class="btn" data-clipboard-target="#' + currentId + '"><img src="https://clipboardjs.com/assets/images/clippy.svg" width="13" alt="Copy to clipboard"></button>';
     $(this).after(clipButton);
  });
 
  new Clipboard('.btn');
   clipboard.on('success', function(e) {
        alert('复制成功')
    });

    //复制失败执行的回调，可选
    clipboard.on('error', function(e) {
        console.log(e);
    });
</script>
{% endif %}
