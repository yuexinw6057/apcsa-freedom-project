# Entry 2
##### 12/19/21

Previously after selecting my tool to learn, I have been following along the tutorial on their website and start 'machine training' aka the google's [teachable machine](https://teachablemachine.withgoogle.com/). I first started off with Ml5's starter code

```
<!DOCTYPE html>
<html>
<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title>ML5 Test</title>
    <meta name='viewport' content='width=device-width, initial-scale=1'>
    <link rel='stylesheet' type='text/css' media='screen' href='main.css'>
    <script src='main.js'></script>
</head>
<body>
    <div>Teachable Machine Image Model</div>
<button type="button" onclick="init()">Start</button>
<div id="webcam-container"></div>
<div id="label-container"></div>
<script src="https://cdn.jsdelivr.net/npm/@tensorflow/tfjs@1.3.1/dist/tf.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@teachablemachine/image@0.8/dist/teachablemachine-image.min.js"></script>
</body>
</html>
```
The following code above imports material from google's learnable machine. In this code it exports the learning data set that I have been 'training' it for. The training process is rather simple, the larger the sample the more accurate it is. Since there are no data set for the American Sign Language(ASL) that looked the way I wanted to look, I started gathering the data.
![image info](machineTeaching.png =250x)


[Previous](entry01.md) | [Next](entry03.md)

[Home](../README.md)