# js_functions
Some helpful functions

1. Redeclare EventListening functions for compatibility

addEventListener()
removeEventListener()

&lt;body onload='javascript:onLoad();'&gt;
&lt;script type="text/javascript"&gt;
function onLoad() {
  addEventListener("change", document.getElementById('elementId'), onElementIdChange);
}
