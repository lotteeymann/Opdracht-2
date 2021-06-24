# Opdracht-2
Shapes

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Hello, WebVR! • A-Frame</title>
    <meta name="viewport" content="width=device-width">
    <script src="https://aframe.io/releases/1.0.4/aframe.min.js"></script>
    <script src="scripts/main.js" defer></script>
  </head>
  <body>
    <a-scene background="color: #333333">
   		<a-circle color="pink" radius="5" position="1 5 1"></a-circle>
   		<a-ring color="blue" radius-inner="1" radius-outer="2" position="4 3 1"></a-ring>
   		<a-sky color="#6EBAA7"></a-sky>
      	<a-box id="myBox"
        	width="3"
        	height="3"
        	depth="3"
        	color="green" 
        	position="1 3 1"
        	shadow>
      	</a-box>
    </a-scene>
  </body>
</html>
