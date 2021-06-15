<div id="cod">
```javascript
/* Global scope: this code is executed once */
const redis = require('redis');

const host = <HOSTNAME>;
const port = <PORT>;
const password = <PASSWORD>;

```
</div>
<button class="btn" data-clipboard-action="copy" data-clipboard-target="#cod">
    copy to clipboard
</button>	
<script src="clipboard.min.js"></script>
 <script>
      var clipboard = new ClipboardJS('.btn');

      clipboard.on('success', function (e) {
        console.log(e);
      });

      clipboard.on('error', function (e) {
        console.log(e);
      });
    </script>

