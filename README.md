<html>
<head></head>
<body>
<iframe id="iframe1" src="https://agar.io" width="100%" height="100%" frameborder="0" scrolling="no"></iframe>
<br><br><br><br><br><br>
<iframe id="iframe2" src="https://agar.io" width="100%" height="100%" frameborder="0" scrolling="no"></iframe>
<br><br><br><br><br><br>
<iframe id="iframe3" src="https://agar.io" width="100%" height="100%" frameborder="0" scrolling="no"></iframe>
<br><br><br><br><br><br>
<iframe id="iframe4" src="https://agar.io" width="100%" height="100%" frameborder="0" scrolling="no"></iframe>
<br><br><br><br><br><br>
<iframe id="iframe5" src="https://agar.io" width="100%" height="100%" frameborder="0" scrolling="no"></iframe>
<br><br><br><br><br><br>
<p style="text-align: center;"><img src="https://jimboy3100.github.io/banners/CropedImage128.gif" alt="Smiley face"><br><a target="_blank" href="http://legendmod.ml"><font color="blue"><b><u>The Legend Mod Project</u></b></font></a>
<br><a style="text-align: center;" href="https://chrome.google.com/webstore/detail/im-not-robot-captcha-clic/ceipnlhmjohemhfpbjdgeigkababhmjc/related" target="_blank" class="logEntry" style="color: lightgrey; font-size: 32px;">ReCaptcha Pass Extension</a></p>
<br>Auto FPS boost when on focus (wait several minutes) Relogin on fb/google. Click on the map on which you want to use keyboard. Download to pc, or use http protocol. Keep Legend Mod enabled. 
<script>
var url = window.location.href;

var region = getParameterByName("r", url);
var realmode = getParameterByName("m", url);
var searchSip = getParameterByName("sip", url);
//var autoplay = getParameterByName("autoplay", url);


if (searchSip!=null){
	if (realmode!=null){
		setTimeout(function() {
		document.getElementById("iframe1").src="https://agar.io/?sip=" + searchSip + "&?r=" + region + "&?m=" + realmode + "&?autoplay=true";
		}, 2000);
		setTimeout(function() { 
		document.getElementById("iframe2").src="https://agar.io/?sip=" + searchSip + "&?r=" + region + "&?m=" + realmode + "&?autoplay=true";
		}, 4000);
		setTimeout(function() {
		document.getElementById("iframe3").src="https://agar.io/?sip=" + searchSip + "&?r=" + region + "&?m=" + realmode + "&?autoplay=true";
		}, 6000);
		setTimeout(function() { 
		document.getElementById("iframe4").src="https://agar.io/?sip=" + searchSip + "&?r=" + region + "&?m=" + realmode + "&?autoplay=true";
		}, 8000);
		setTimeout(function() { 
		document.getElementById("iframe5").src="https://agar.io/?sip=" + searchSip + "&?r=" + region + "&?m=" + realmode + "&?autoplay=true";
		}, 10000);
		}
	else{
		setTimeout(function() {
		document.getElementById("iframe1").src="https://agar.io/?sip=" + searchSip + "&?autoplay=true";
		}, 2000);
		setTimeout(function() {
		document.getElementById("iframe2").src="https://agar.io/?sip=" + searchSip + "&?autoplay=true";
		}, 4000);
		setTimeout(function() {
		document.getElementById("iframe3").src="https://agar.io/?sip=" + searchSip + "&?autoplay=true";
		}, 6000);
		setTimeout(function() {
		document.getElementById("iframe4").src="https://agar.io/?sip=" + searchSip + "&?autoplay=true";
		}, 8000);
		setTimeout(function() {
		document.getElementById("iframe5").src="https://agar.io/?sip=" + searchSip + "&?autoplay=true";
		}, 10000);
	}
}

function getParameterByName(name, url) {
    if (!url) url = window.location.href;
    name = name.replace(/[\[\]]/g, "\\$&");
    var regex = new RegExp("[?&]" + name + "(=([^&#]*)|&|#|$)"),
        results = regex.exec(url);
    if (!results) return null;
    if (!results[2]) return '';
    return decodeURIComponent(results[2].replace(/\+/g, " "));
}
</script>
  
</body>
</html>
