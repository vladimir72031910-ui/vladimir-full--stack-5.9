[2.0-vovalend.html](https://github.com/user-attachments/files/26704172/2.0-vovalend.html)
<!DOCTYPE html>
<!-- saved from url=(0032)http://127.0.0.1:5501/index.html -->
<html lang="en"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>vovalend</title>
    <link rel="stylesheet" href="./2.0-vovalend_files/style.css">
    <link rel="stylesheet" href="./2.0-vovalend_files/Barlow-Black.otf">
</head>
<body>
    <main class="main">

    <article class="list">

        <section class="foto">
             <img src="./2.0-vovalend_files/bg.jpg" alt="bg.jpg" class="bg">
             <img src="./2.0-vovalend_files/logo.svg" alt="logo" class="logo"> 

        </section>
        

        <section class="words">

            <div class="get">
                <h1 class="texth1">Get iintoo it today</h1>

                <h2 class="texth2">There is no charge or obligation upon registration</h2>
            </div>
            
        
            <div class="regis">
              <img src="./2.0-vovalend_files/facebook.svg" alt="facebook" class="facebook">
              <a href="https://facebook.com/" class="ftex">Register with Facebook</a>
            </div>

            <div class="khox">
              <img src="./2.0-vovalend_files/linkedin (1).svg" alt="linkedin" class="link">
              <a href="https://youtu.be/axMAWQC7r9Y" class="vyachekhox">Register with Linkedin</a>
            </div>
            
            <div class="lineor">
              <span class="lol"></span>
              <span class="or">OR</span>
            <span class="lol"></span>
            </div>

            <div class="eml">
              <label for="Email" class="igor">Email</label>
              <input type="email" class="Email" name="Email" placeholder="gus.goodwin@gmail.com" required="">
            </div>

            <div class="toy">
              <label for="number" class="pho">Phone</label>
              <input type="number" name="Phone" class="phone">
            </div>

             <div class="face2"> 
              <h1 class="texth1">What type of investor are you?</h1>
              <h2 class="texth2">Select the type of investor you are below.</h2>
            </div> 
            

 <div class="radio">

     <div class="rop">
                

            <span class="yoga">
             <input type="radio" id="individual" name="investor" value="indi" checked="">
             <label for="individual" class="mama">individual</label>
            </span>

            <span class="Busines">   
             <input type="radio" id="Business" name="investor" value="Business"> 
             <label for="Business" class="mama">Business</label>
            </span>

            <span class="ira">
             <input type="radio" id="IRA" name="investor" value="IRA"> 
             <label for="IRA" class="mama">IRA</label>
            </span>

            <span class="tras">
             <input type="radio" id="Trust" name="investor" value="Trust">
             <label for="Trust" class="mama">Trust</label>
            </span>
     </div>

 </div>
        
        <div>
         <input type="text" id="tx" name="text" placeholder="I am a natural person investing on my own behalf as a sole owner, join tenant, or tenant in common. " required="">
         <label for="tx"></label>
         </div>
         <div class="you">
            <input type="checkbox" id="check" name="check">
            <label for="check" class="iintoo">I agree to the terms and receiving notifications from iintoo <a href="https://youtu.be/whAGVUnFXfA" class="kuplonov">View full terms</a></label>
         </div>

      <div>
            <button type="submit" class="gold"> Create Account</button>
         </div> 

        </section>

    </article> 

    </main>

<!-- Code injected by live-server -->
<script>
	// <![CDATA[  <-- For SVG support
	if ('WebSocket' in window) {
		(function () {
			function refreshCSS() {
				var sheets = [].slice.call(document.getElementsByTagName("link"));
				var head = document.getElementsByTagName("head")[0];
				for (var i = 0; i < sheets.length; ++i) {
					var elem = sheets[i];
					var parent = elem.parentElement || head;
					parent.removeChild(elem);
					var rel = elem.rel;
					if (elem.href && typeof rel != "string" || rel.length == 0 || rel.toLowerCase() == "stylesheet") {
						var url = elem.href.replace(/(&|\?)_cacheOverride=\d+/, '');
						elem.href = url + (url.indexOf('?') >= 0 ? '&' : '?') + '_cacheOverride=' + (new Date().valueOf());
					}
					parent.appendChild(elem);
				}
			}
			var protocol = window.location.protocol === 'http:' ? 'ws://' : 'wss://';
			var address = protocol + window.location.host + window.location.pathname + '/ws';
			var socket = new WebSocket(address);
			socket.onmessage = function (msg) {
				if (msg.data == 'reload') window.location.reload();
				else if (msg.data == 'refreshcss') refreshCSS();
			};
			if (sessionStorage && !sessionStorage.getItem('IsThisFirstTime_Log_From_LiveServer')) {
				console.log('Live reload enabled.');
				sessionStorage.setItem('IsThisFirstTime_Log_From_LiveServer', true);
			}
		})();
	}
	else {
		console.error('Upgrade your browser. This Browser is NOT supported WebSocket for Live-Reloading.');
	}
	// ]]>
</script>

</body></html>
