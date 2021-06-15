```javascript
/* Global scope: this code is executed once */
const redis = require('redis');

const host = <HOSTNAME>;
const port = <PORT>;
const password = <PASSWORD>;

...
```
{: #code-example-1}

<script src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/clipboard@1/dist/clipboard.min.js"></script>
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
</script>
{% endif %}

<code>print("Club Nacional de Football")</code>
<br>
<code>print("is a sports institution")</code>
<br>
<code>print("from Uruguay")</code>
