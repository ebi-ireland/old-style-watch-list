<main>
<!--Setting/start app Pannel-->
<!--Main Pannel-->
	<h1 class="foryou center">For You</h1>
	<div class="filmimages"></div>
	<!--Images-->
	<div class="filmimageaction">
		<div class="filmimages"></div>
	</div>
	<!--Film Title-->
	<div class="filmtitleaction">
		<div class="filmtitle">This space writes the film title</div>
	</div>	
	<!--4 circles button, good review save share-->
	<div class="circleaction">
		<div class="circle good"></div>
		<div class="circle reviews"></div>
		<div class="circle saved"></div>
		<div class="circle share"></div>
	</div>
	<!--Descriptions-->
	<div class=descriptionarea>
		<div class="descriptions">This is the description space.</div>
	</div>
<!--Reviews Pannel-->
<!--Login Pannel-->
	<!--User Icon-->
	<!--Username-->
	<!--Saved Films-->
	<!--How to Use this app-->
	<!--Log out-->
<!--Register / Login Pannel-->
	<!--If users have not register/login a account, app display a R/L pannel-->


<!--CSS script-->
<script>
var styles = `
		main {
			position: relative;
      height: 100vh;
      width: 100vw;
      overflow: hidden;
			background-color: #000000;
		}
    .foryou { 
        font-size:50px;
    }
		.center {
			text-align: center;
      display: flex;
      justify-content: center;
      gap: 15px;
		}
		.filmimages {
		
		}
		.circleaction {
		position: absolute;
    right: 15px;      
    bottom: 100px;    
    display: flex;
    flex-direction: column; 
    gap: 20px;       
    z-index: 20;
		}
		.circle {
			width: 55px;
      height: 55px;
      border-radius: 50%;
      background: rgba(255, 255, 255, 0.15);
      border: 2px solid white;
      display: flex;
      align-items: center;
      justify-content: center;
      cursor: pointer;
		}
		.good {
		
		}
		.reviews {
		
		}
		.saved {
		
		}
		.share {
		
		}
		.filmtitleaction {
			position: absolute;
      top: 50%;
      left: 50%;
			transform: translate(-50%, -50%);
			text-align: center;
			z-index: 50;
		}
		.filmtitle {
		bottom: 20px;
		left: 50px;
		z-index: 15;
		}
		.descriptionarea {
			position: absolute; 
      bottom: 40px; /* 下からの位置 */
      left: 50px;
      z-index: 20;
		}
		.descriptions {
       font-size: 16px;
		}
		
`

var styleSheet = document.createElement("style")
styleSheet.textContent = styles
document.head.appendChild(styleSheet)
</script>
</main>