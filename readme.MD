# Video Content Duration Measuring Tool

This project was created during Kaunas Coding School course.

Aim of this project is to create Python program to measure the duration an object is visible in a given video.

### Important!
**Python version 3.6 is needed. (Tensorflow only supports python up to 3.6)**

**How to run**

1. Install the following libraries:
	`pip install -r requirements.txt
2. If you have your own model for detecting objects, add the model file to the same folder as the project and change the following line:
`detector.setModelPath(execution_path + "\\your_model.h5")`

3. Add the video, that you want to measure, to the same folder as the project and then edit the following line:
`input_file_path=(execution_path + "\\your_video.mp4")`

4. Run Main.py. After the process is finished you will find result in Result.txt and you can check the video, with marked objects, in the output folder.

**Resources:**
https://medium.com/@guymodscientist/image-prediction-with-10-lines-of-code-3266f4039c7a
https://docs.opencv.org/master/d1/dc5/tutorial_background_subtraction.html
https://github.com/OlafenwaMoses/ImageAI/blob/master/imageai/Detection/VIDEO.md
https://github.com/OlafenwaMoses/ImageAI
https://medium.com/coinmonks/detecting-custom-objects-in-images-video-using-yolo-with-darkflow-1ff119fa002f
