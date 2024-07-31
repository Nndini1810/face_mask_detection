<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
        
</head>
<body>

<h1>Mask Detection Using Deep Learning</h1>

<p>This repository contains code for training a mask detection model using deep learning. The project includes training a model to detect whether a person is wearing a mask or not, and using the trained model to detect masks in video streams.</p>

<h2>Usage</h2>

<h3>Training</h3>
<p>To train the mask detection model, use the <code>train_mask_detector.py</code> script. This script trains a deep learning model on a dataset of images with and without masks.</p>

<div class="code-block">
<pre><code>python train_mask_detector.py</code></pre>
</div>

<h3>Detection</h3>
<p>To detect masks in a video stream, use the <code>detect_mask_video.py</code> script. This script utilizes the trained model to perform real-time mask detection.</p>

<div class="code-block">
<pre><code>python detect_mask_video.py</code></pre>
</div>

<h2>Results</h2>

<p>Below is a sample plot showing the training loss and accuracy of the model:</p>

<div class="image">
    <img src="./plot.png" alt="Training Loss and Accuracy">
</div>

</body>
</html>
