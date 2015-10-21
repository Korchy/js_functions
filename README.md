# js_functions
Some helpful functions

1. Redeclare EventListening functions for compatibility
---

<b>addEventListener(event, element, function);<br>
removeEventListener(event, element, function);</b><br>

&lt;body onload='javascript:onLoad();'&gt;<br>
&lt;script type="text/javascript"&gt;<br>
function onLoad() {<br>
  addEventListener("change", document.getElementById('elementId'), onElementIdChange);<br>
}<br>
&lt;/script&gt;
