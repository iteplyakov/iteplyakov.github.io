<html>
	<head>
		<style>

			.background {
				position: absolute;
				left: 0px;
				top: 0px;
				width: 1920px;
				height: 1080px;
				z-index: 1;
			}
			.data {
				position: absolute;
				left: 0px;
				top: 0px;
				width: 1920;
				height: 1080;
				z-index: 5;
				background-color: transparent;
				
			}

			.tyytdactual {
				position: absolute;
				left:600px;
				top: 500px;
				font-family: "Avenir Next", avenir, serif;
				font-size: 64px;
				font-weight: bold;
				animation-name: fadeInLY;
			    animation-duration: 5s;
			    animation-delay: 5.5s;
			    animation-fill-mode: both;

				color: white;
				z-index: 10;
			}
			
		
			.lyytdcomp {
				position: absolute;
				left: 1200px;
				top: 500px;
				font-family: "Avenir Next", avenir, serif;
				font-size: 64px;
				font-weight: bold;
				animation-name: fadeInLY;
			    animation-duration: 4s;
			    animation-delay: 6.5s;
			    animation-fill-mode: both;

				color: white;
				z-index: 10;
			}
			
		

			
			progress[value]::-webkit-progress-bar {
				background-color: transparent;
		
			}

			progress[value]::-webkit-progress-value {
				background-color: white;
				opacity: 1;
			}

			#circle1 {
				position: absolute;
				z-index: 150;
				left: 900px;
				top: 637px;
				width: 300px;
				height: 300px;
				border-radius: 250px/250px;
				background-color: white;
				color: black;
				animation: fadeIn 1s linear;
				animation-fill-mode: both;
				animation-delay: .5s;
				font-family: "Avenir Next", avenir, serif;
				font-size: 40px;
				font-weight: bold;
			}

			#pif[value] {
				-webkit-appearance: none;
				position: absolute;
				transform: rotate(-90deg);
				z-index: 145;
				left: 760px; top: 420px;
				width:575px; height: 120px;
				background-color: tranparent;
				color: white;
				animation: fadeIn 1s linear;
				animation-fill-mode: both;
				animation-delay: .5s;
			}
			
			.lastmod {
				position: absolute;
				font-size: 10px;
				left;
				bottom: 20px;
				color: black;
				animation: fadeIn 1s linear;
				animation-fill-mode: both;
				animation-delay: .5s;
				z-index: 20;
				font-family: "Avenir Next", avenir, serif;
			}
			
			@keyframes store-commitment{
				0%{transform: translate(-1600px, 340px);}
				100%{transform: translate(0px, 340px);}
			}

			@keyframes tyytdactual{
				0%{transform: translate(-1600px, 456px);}
				100%{transform: translate(0px, 456px);} 
			  
			}
			
			@keyframes lyytdcomp{
				0%{transform: translate(-1600px, 572px);}
				100%{transform: translate(0, 572px);}
			}
			
		
			
			@keyframes fadeInLY {
				0% {opacity: 0;}
				25% {opacity: 1;}
				75% {opacity: 1;}
				100% {opacity: 0;}
			} 
			
			.button {
			  position: absolute;
			  left: 1625px;
			  top: 715px;
			  border: none;
			  background-color: white;
			  color: black;
			  width: 200px;
			  height: 200px;
			  text-align: center;
			  text-decoration: none;
			  display: inline-block;
			  font-size: 32px;
			  border-radius: 50%;
			  font-family: "Avenir Next", avenir, serif;
			  animation: fadeIn 1s linear;
			  animation-delay: .5s;
			  z-index: 20;
			}
		</style>
	</head>
	<body>


		<div class="background">
			<video autoplay width="1920" height="1080" muted playsinline>
				<source src="https://d2tzxabzwh7zni.cloudfront.net/53963fd4-59bb-4e90-8b7d-6923af05787a/G3FPLAzVv-tbty.mp4-1602087006824.optimized.mp4" type="video/mp4">
			</video>
		
		</div>		
		
		
		
		

	<div class="data">
		<div class="tyytdactual">10%</div>
		<div class="lyytdcomp">40%</div>
	</div>


	</body>
</html>
			
	



