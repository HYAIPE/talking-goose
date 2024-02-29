<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<h1>Talking Goose Tutorial</h1>
<p>Welcome to the Talking Goose tutorial! In this guide, we'll walk you through setting up an animated talking goose using OBS Studio, the Move Transition plugin, and some custom assets. Make sure to follow each step closely to achieve the best results.</p>

<h2>Prerequisites</h2>
<p>Before we start, ensure you have the following:</p>
<ul>
    <li><strong>OBS Studio</strong>: Download and install from <a href="https://obsproject.com/">OBS Project</a>.</li>
    <li><strong>Move Transition Plugin</strong>: Download from <a href="https://obsproject.com/forum/resources/move.913/">OBS Project Forum</a>.</li>
    <li><strong>Assets</strong>: Download the assets attached to this tutorial.</li>
</ul>
<p>For reference, we will be following the instructions provided in this video: <a href="https://www.youtube.com/watch?v=vsRlOkyVqU4">How to Create a OBS Animation</a>.</p>

<h2>Setup Guide</h2>

<h3>Step 1: Import Files</h3>
<p>Start by importing the provided assets into OBS.</p>

<h3>Step 2: Order Your Files</h3>
<p>Arrange your files in numerical order from 1 to 4.</p>

<h3>Step 3: Group Your Items</h3>
<ul>
    <li>Select the first image.</li>
    <li>Hold the SHIFT key and select image 4.</li>
    <li>Right-click and choose <strong>'Group Selected Items'</strong>.</li>
</ul>

<h3>Step 4: Center Items</h3>
<ul>
    <li>With the group selected, press CTRL+D, or:</li>
    <li>Right-click, hover over 'Transform', and select <strong>'Center to screen'</strong>.</li>
</ul>

<h3>Step 5: Position Your Items</h3>
<p>With all items selected and centered, drag them slightly down to align the geese with the bottom of the screen.</p>

<h3>Step 6: Adjust Opacity</h3>
<ul>
    <li>Select item 2, labeled 'the open mouth'.</li>
    <li>Click on 'Filters' and select 'Color Correction'.</li>
    <li>Set the opacity to 0 by dragging the slider.</li>
</ul>

<h3>Step 7: Add Audio Input Source</h3>
<p>In the 'Sources' panel, add a new source and select 'Audio Input'. You can adjust the microphone settings by selecting the three dots under the 'Audio Mixer' for mic/aux.</p>

<h3>Step 8: Add Audio Move Filter</h3>
<ul>
    <li>Select 'mic/aux' under 'Sources'.</li>
    <li>In the lower left corner, add the audio filter 'Audio Move'.</li>
</ul>

<h3>Step 9: Configure Audio Move</h3>
<p>Set up the 'Audio Move' filter with the following settings:</p>
<ul>
    <li><strong>Meter Type</strong>: Magnitude</li>
    <li><strong>Adjust Easing</strong>: Set to your liking, 15 is recommended.</li>
    <li><strong>Action</strong>: Filter Enable</li>
    <li><strong>Source</strong>: 2-open-mouth.png</li>
    <li><strong>Filter</strong>: Color Correction</li>
    <li><strong>Threshold Action</strong>: Enable Under and Disable Over</li>
    <li><strong>Threshold</strong>: Adjust to your liking, 6 is recommended.</li>
</ul>

<h2>Completion</h2>
<p>Congratulations! You should now have a talking goose in your scene. Feel free to adjust the settings further to match your preferences and have fun with your new animated companion!</p>

</body>
</html>
