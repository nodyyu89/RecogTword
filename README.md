# RecogTword
A simple OCR project, aimming to recognize handwritten english letters


This is a simple project finished during in my internship working. The project is called RecogTword. The letter 'T' has two meaning.
One is the word 'The' ,while the other one is the first letter of a person who has made a significant development on Hao's will

The aim of this object is to recognize handwritten English letters.

# File description

-guipy.py : the main gui file, you can just run it in the same file folder if you want a quick review

-draggable_rectangle2.py : In the gui file, you have to drag and draw a rectangle to locate the area that the handwritten objects is located

-self_trained_model_alphrbet2.py : it is a py script to train a model which can recognize handwritten objects with the use of CNN model and keras library.

-A-E_model.h5 , modelA-E.json : a trained model by keras

-image_data : some English letters jpg data, it is recommended to add your data in order to train a better model

# Required library

-numpy, keras, tensorflow, PIL, matplotlib, PyQt5, python 3.5+
