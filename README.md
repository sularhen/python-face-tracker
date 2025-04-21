## Python Face Recognition

***Face recognition for images or videos using python and opencv libraries. the principal objetive with this code
was to track faces in videos and save it as images when the target is the correct. I did it using python, Open
CV libraries (haar classifiers) and ArcFace model for embeeding. you can use it for tracking faces in images too.**

## How to use it:

- Copy and paste the code in your favorite code editor.
 - Save to code in a folder of your preference.
 - Change the route of your video or image in the code.
 - Put your path direction of the haar cascades in the code.
 - Be aware that the video is in mp4 format or the images are in jpg or png format.
 - In case you want to track faces in images then create a folder with the images and add the path to the code.
 - Run te code.
 - A folder is going to be created automatically with the faces saved in it in case you want to track faces in video.

### TO RUN THIS CODE CORRECTLY YOU NEED TO HAVE:

***1. have the ArcFace model (arcfaceresnet100-8.onnx) in the folder where you save the code:***

 -Download the model from a trusted repository (such as ONNX Model Zoo or ArcFace resources).
 - Make sure to save the file in the same path as your script or set onnx_model_path to the correct location.

***2. Download the Haar Cascade Classifiers and remember their path as you must provide them in the code for it to work:***

 - These .xml files come with OpenCV and are located in the cv2/data directory of your Python environment. Be sure to check the paths in the variables:

     haarcascade_frontalface_default.xml
     haarcascade_profileface.xml

 - If you can't find them, you can download them from the official OpenCV repository, remember that you must provide the path to these cascades in the code for it to run correctly so remember the path address.

***3. Make sure that the video format is MP4 and that it is saved in the folder where you will save the code and the faces. and the images
   are in jpg or png format.***

***4. Have an env environment created in conda with your favorite code editor (optional).***
 
- If you want to configure VS Code with a conda environment, you can find the necessary documentation at: https://docs.anaconda.com/working-with-conda/ide- tutorials/vscode/


#### ***Feel free, to change this code and play with it.***

Sularhen.
