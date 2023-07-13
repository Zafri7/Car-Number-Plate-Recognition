# Car-Number-Plate-Recognition
Areas of this project: Image Processing &amp; Deep Learning
<br>
<br>
This project has 2 major sections: extraction of number plate and character recognization
<h3>Extraction</h3>
Refer to the folder extraction output to see the how the number plate is extracted step-by-step.
<ol>
  <li>convert to grayscale</li>
  <li>canny edge detection</li>
  <li>binarize image using Otsu's binarization</li>
  <li>Erosion</li>
  <li>Dilation</li>
  <li>Blob analysis to detect the largest component</li>
</ol>
<h3>Character recognization</h3>
Uses an artificial neural network, trained on alphabet and number dataset
