# Three.js Pentagon Shape with Rotation

## Overview

This project demonstrates how to create a 3D pentagon shape using **Three.js** and animate it by rotating on both the X and Y axes. The shape is rendered with a red material, and users can interact with the 3D scene using the **OrbitControls** to spin, zoom, and pan the camera view.

## Features

- Creates a **pentagon shape** using polar coordinates.
- The pentagon is rendered with a **red material** (modifiable).
- **Rotation** animation is applied to the pentagon on both the X and Y axes.
- Users can interact with the scene using **OrbitControls** (zoom, pan, and rotate the view).
- The scene is rendered with **WebGL** via Three.js.

## Prerequisites

Before running the code, make sure your environment supports the following:

- **A modern web browser** (e.g., Chrome, Firefox, Edge)
- **Internet connection** for loading external libraries via CDN (Three.js, OrbitControls)

## Installation and Setup

1. **Clone the repository** (if applicable) or simply copy the code below into a new `.html` file.
2. Open the file in your web browser.

## Usage

### 1. **HTML Structure**

This section of the code sets up the basic structure of the page and links the required external libraries:

```html
<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="UTF-8" />
		<meta name="viewport" content="width=device-width, initial-scale=1.0" />
		<title>Sample Three.js</title>
		<style>
			body {
				margin: 0;
			}
			canvas {
				display: block;
			}
			#container {
				background: #000000;
				width: 100%;
				height: 100%;
			}
		</style>
	</head>
	<body>
		<div id="container"></div>
		<!-- External Scripts -->
		<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.5.1/jquery.min.js"></script>
		<script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>
		<script src="https://cdn.jsdelivr.net/npm/three@0.128.0/examples/js/controls/OrbitControls.js"></script>
		<script type="text/javascript">
			<!-- JS Code Here -->
		</script>
	</body>
</html>
```
