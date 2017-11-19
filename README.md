javascript: (function() {
    var url = location.href;
    var width = 600;
    var height = 400;
    var left = parseInt((screen.availWidth/2) - (width/2));
    var top = parseInt((screen.availHeight/2) - (height/2));
    var windowFeatures = "width=" + width + ",height=" + height +   
							",status,resizable,left=" + left + ",top=" + top + 
							"screenX=" + left + ",screenY=" + top + ",scrollbars=no,menubar=no,titlebar=no,toolbar=no,location=no";
	window.open(url, "subWind", windowFeatures, "POS");
})();
