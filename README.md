# asl-validator
American Sing Language Validator

This is a prototype for real-time ASL alphabet recognition. It is meant to provide an automatic feedback mechanism for ASL learners with use of only a web camera.
Currently it support only static signs of ASL alpabet.
![image](https://user-images.githubusercontent.com/40677903/171730881-6ec40b7e-e5c4-48e4-b08b-f665f2108c2b.png)

## Dependencies used in this project:
- Python https://www.python.org/
- Conda https://anaconda.cloud/getting-started-with-anaconda-individual-edition
- Jupyter Notebook https://jupyter.org/
- Tensorflow https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/install.html
- Tensorflow Records https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/training.html#create-tensorflow-records
- OpenCV https://opencv.org/
- NumPy https://numpy.org/
- MediaPipe https://google.github.io/mediapipe/
- Scikit-Learn https://scikit-learn.org/stable/
- Matplotlib https://matplotlib.org/

## How to run and update the script:
- Run Anaconda command in the terminal to start Tensorflow: conda activate tensorflow
- Launch Jupiter notebook by running a command: jupyter notebook
- After a new browser window open one of the scripts, either asl-validator-initial.ipynb or asl-validator-DEV-vNext.ipynb
- Run sells, consult the comments, section 5 "Collect Data" should be skipped if data collection is not needed

## Code structure:
- jupyer notebook script(s)
- [data] folder that contains dataset, each sign has corresponding sequences/videos per sign in a separate folder and each of the folders contain NumPY files for each frame
- [logs] folder, contains information on training process, generated when script is ran should be openened using TensorBoard, using command 'tensorboard --logdir "asl-validator/logs"'
- 

*For more information on how to work with Jupiter Notebook consult https://jupyter.org/

https://user-images.githubusercontent.com/40677903/171731664-48ca3556-c3e3-4457-961a-faab84caf34f.mp4

https://user-images.githubusercontent.com/40677903/171732403-b97bc490-2fda-4431-8f85-0e47b76d27d1.mp4

