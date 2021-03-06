## Mask-Detector 
### Live demo via Laptop webcam:
<img src="https://github.com/Mainakdeb/mask-detector/blob/master/gifs/laptop-webcam-demo.gif" width=50% height=50%>

### Live demo via smartphone:
<img src="https://github.com/Mainakdeb/mask-detector/blob/master/gifs/mobile-app-demo.gif" width=20% height=20%>


Our solution contains 2 packages
1. A computer vision based script that detects specific facial features from a video feed. It determines the of the person/persons in the video frame is wearing a face mask or not within milliseconds for each frame input and requires minimal computational resources for each iteration. 

2. A Flutter based mobile application that uses the camera or the gallery to detect face masks and reminds the user if he/she is not wearing a mask. 


### Plugins Used for the flutter app:rocket: ##
<ul>
  <li><a href ='https://pub.dev/packages/cupertino_icons'>Cupertino Icons</a></li>
  <li><a href='https://pub.dev/packages/camera'>Camera</a></li>
  <li><a href='https://pub.dev/packages/image_picker'>Image-Picker</a></li>
  <li><a href='https://pub.dev/packages/tflite'>Tflite</a></li>
 </ul>
<h3>How does the Android Application work:</h3>
<ul>
  <li> At first we open the application.</li>
  <li>After opening you will be welcomed by the main page UI.</li>
  <li>You see two options either to predict using an existing image or by live camera.</li>
  <li>you choose the method you prefer</li>
  <li>You will be able to see whether you are wearing mask or not.</li>
 </ul>
<h3> Steps for using</h3>
<ul>
  <li>Clone the repo</li>
  <li>Open Android Studio</li>
  <li>Open Project</li>
  <li>Go to the location where you have saved the project</li>
  <li>Go to the flutter-app folder.That is the main project</li>
  <li>Connect to emulator or mobile through USB to use the app after running  successfully</li>
</ul>
<h3> Possible Errors </h3>
<ul>
  <li>If you get compatibility issues go to android folder, right click and click on migrate and then migrate project to Android X.</li>
  <li>This project uses the Dart SDK so make sure you have it installed.</li>
  <li>Some plugins might require minSdkVersion 21 so make sure to change that in build.gradle file.</li>
  <li>Before running the app go to pubspec.yaml file and click on the light bolt sign in the dependencies section and it will suggest to run pub get.Press on it so that you have the dependencies installed</li>
  <li>Make sure you have given access for installing through USB.If not change it in developer options in your mobile.</li>
 </ul>
 <h3>Source for Plugins and Flutter SDK</h3>
 <ul>
 <li><a href='https://flutter.dev/'>Flutter</a></li>
 <li><a href='https://flutter.dev/docs/get-started/install'>Get started with flutter</a></li>
 <li><a href='https://pub.dev/'>Pub.dev for plugins</a>
 <li><a href="https://dart.dev/get-dart">Dart SDK</a></li>
 </ul>
<h3>Screenshots of the App</h3>
<h4>Welcome Screen</h4>
<img src="https://user-images.githubusercontent.com/53183532/94363423-a15f0c80-00df-11eb-8b5f-3d2da1dbe440.png" width=20% height=20%>
<h4>Predict By Image</h4>
<img src="https://user-images.githubusercontent.com/53183532/94363440-bb98ea80-00df-11eb-81c1-3e9cb67cb5cd.png" width=20% height=20%>

### Group-Members On Board:-
- Mainak Deb
- Giwansh Aryan
- Rishab Mudliar
- Siddharth Cilamakoti
- Sanjay Thiyagarajan
- Navneet Kumar Singh
