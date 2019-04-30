# Computer-Assisted-Police-Sketching-with-GAN
<h2>Computer Assisted Police Sketching Using Generative Adversarial Networks</h2>

“Computer Assisted Police Sketching using Generative Adversarial  Networks” - The objective of this project was to create an application using Generative Adversarial Networks that would be able to generate unique and arbitrary images of fake human faces. This would be possible through the use of several sliders present in the application, each responsible for altering an individual (or multiple, in some cases) facial feature like Skin Tone, Facial Hair Length, Shape of the Head, etc. A user will thus be able to adjust the different sliders and create a completely random human face, for every slider configuration. These images, although completely fake, can resemble actual people. As a result, this application can be directly used to create police sketches of persons of interest. These sketches are better than hand drawn sketches due to the fact that the images created using the application is almost instantaneous and being a computer application, will be more convenient and practical to use. 

<h2>Group Members: </h2>
<ul>
  <li> Malayanil Senapati </li>
  <li> Romit Ghosh </li>
  <li> Sohag Baral </li>
</ul>
  
 <h2>Examples of Faces Generated by the GAN and then fine tuned with the sliders.</h2>
 <ol>
    <li> <img src = "https://github.com/sohagbaral/Computer-Assisted-Police-Sketching-with-GAN/blob/master/Generated%20Faces/Gen_1.jpg" height = 200 width = 220> </li> <br>
    <li> <img src = "https://github.com/sohagbaral/Computer-Assisted-Police-Sketching-with-GAN/blob/master/Generated%20Faces/Gen_2.jpg" height = 200 width = 220> </li> <br>
    <li> <img src = "https://github.com/sohagbaral/Computer-Assisted-Police-Sketching-with-GAN/blob/master/Generated%20Faces/Gen_3.jpg" height = 200 width = 220> </li> <br>
    <li> <img src = "https://github.com/Malayanil/sohagbaral/Computer-Assisted-Police-Sketching-with-GAN/blob/master/Generated%20Faces/Gen_4.jpg" height = 200 width = 220> </li> <br>
    <li> <img src = "https://github.com/sohagbaral/Computer-Assisted-Police-Sketching-with-GAN/blob/master/Generated%20Faces/Gen_5.jpg" height = 200 width = 220> </li> <br>
    <li> <img src = "https://github.com/sohagbaral/Computer-Assisted-Police-Sketching-with-GAN/blob/master/Generated%20Faces/Gen_6.jpg" height = 200 width = 220> </li> <br>
    <li> <img src = "https://github.com/sohagbaral/Computer-Assisted-Police-Sketching-with-GAN/blob/master/Generated%20Faces/Gen_7.jpg" height = 200 width = 220> </li> <br>
 </ol>
 
 <h2>Epochs VS Error Graph.</h2>
 <img src = "https://github.com/sohagbaral/Computer-Assisted-Police-Sketching-with-GAN/blob/master/X-Epochs%20vs%20Y-Error.png">
 <p> The X-Axis represents the number of Epochs and the Y-Axis represents the Error (MSE). </p><br>
 
 <h2>The Model (Generator)</h2>
 <img src = "https://github.com/sohagbaral/Computer-Assisted-Police-Sketching-with-GAN/blob/master/Model%20PNG.png" height = 1200 width = 400>
 <p> We have used Keras Sequential Model and the layer design is shown in this picture. </p><br>
 
 <h2>For further details, please refer to the Report.pdf file uploaded here. </h2>
