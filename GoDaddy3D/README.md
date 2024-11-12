# GoDaddy3D

### Tutorial to Get Started 
```html
<!DOCTYPE html>
<html lang = "en">
<head>
    <meta charset="UFT-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Model Viewer</title>
    <script type="module" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.js"></script>
    <style>
        model-viewer{
            width: 400px;
            height: 600px;
            margin: 0 auto;
        }
    </style>
</head>
<body>
    <model-viewer src="assets/the_creation_of_adam/scene.gltf" camera-controls auto-rotate></model-viewer>
</body>
</html>
```