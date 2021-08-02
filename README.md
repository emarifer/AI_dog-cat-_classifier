# EXAMPLE OF APPLICATION WITH CONVOLUTIONAL NEURONAL NETWORK (CNN)

------------

## Classification of dogs and cats

#### It is a real-time cat and dog classifier with color images. It can be used on the cell phone, just point the camera at the dog or cat that you want to classify (it can be a computer image, a photo, or a real one), it does everything in the browser using Tensorflow.js, based on a model trained in Python with Tensorflow. You can see the CNN model <a href="https://colab.research.google.com/drive/1dSnMDWLlbXiW3_9nYjQFkasxC72ucD-h" target="_blank" rel="noopener noreferrer">here</a>.

### How to use

#### Download the repository wherever you like on your computer

#### Start a server in the folder.
This project uses a Tensorflow.js model, which to load requires access via http / https.
For that you can use any server, but here is a way to do it
- Download Python on your computer
- Open a command line or terminal
- Navigate to the folder where you downloaded the repository
- Execute the command:
```
    python -m http.server 8000 // port example
```
- Open a browser and go to http://localhost:8000