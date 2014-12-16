GDSA
====
This project is based on the work done on MediEval 2013 Pyxel code, so the first you have to do is to download the library Pyxel in here: https://bitbucket.org/emohe/pyxel/src

In this library, we have different modules and tool for the using and development of our project. Also, we have to download other librarys like OpenCV, Scikit sklearn, Numpy and Scipy.

Main Functions, opening the Python editor:

Open "Descriptor.py", run and obtain the decriptor files for each event type. For obtaining the metadata we have 4 files named: Datasets, Vocabulary, Bof and TF-IDF.

Classification, run changing the file path and obtain the file results. For creating a file with the format event_type + #tags of each type of image. Implemented with 4 files named Models, Annotation, Ontology and Detector.

Open "Avaluador.py", run changing the file path and obtain the results, images and files.

The evaluation system used for this project returns the F-score with the Precision and Recall, and the Accuracy. The code shows the information in a visual way through graphs when it’s executed.
