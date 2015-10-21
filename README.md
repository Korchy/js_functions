# js_functions
Some helpful functions

1. Redeclare EventListening functions for compatibility

addEventListener()
removeEventListener()

<body onload='javascript:onLoad();'>
<script type="text/javascript">
function onLoad() {
  addEventListener("change", document.getElementById('elementId'), onElementIdChange);
}
