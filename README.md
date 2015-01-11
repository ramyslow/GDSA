GDSA
====
This project is based on the work done on MediaEval 2013 Pyxel code, so the first you have to do is to download the library Pyxel in here: https://bitbucket.org/emohe/pyxel/src

In this library, we have different modules and tool for the using and development of our project. Also, we have to download other librarys like OpenCV, Scikit sklearn, Numpy and Scipy.

Main Functions, opening the Python editor:

Open "Descriptor.py", run and obtain the decriptor files for each event type. For obtaining the metadata we have 4 files named: Datasets, Vocabulary, Bof and TF-IDF. We did not execute the TF-IDF as the results in that part did not modify successfully the final results (the files .txt were all 'NonEvent')

Classification, run changing the file path and obtain the file results. For creating a file with the format event_type + #tags of each type of image. Implemented with 4 files named Models, Annotation, Ontology and Detector.

Open "Avaluador.py", run changing the file path and obtain the results, images and files.

The evaluation system used for this project returns the F-score with the Precision and Recall, and the Accuracy. The code shows the information in a visual way through graphs when it’s executed.

_____________

Aquest projecte està basat en el treball creat al MediaEval del 2013, utilitzant codi Pyxel de Python, així que el primer que s'ha de fer per poder fer servir aquest repositori es baixar-se la llibreria Pyxel: https://bitbucket.org/emohe/pyxel/src

Dins aquesta llibreria, hi ha diferents modules i tools per l'ús i desenvolupament del nostre projecte. També, ens hem de descarregar altres llibreries com podrien ser l'OpenCV, Scikit sklearn, Numpy and Scipy.

Funcions principals, obrint l'editor de Python:

-Obrint el "Descriptor.py", executem i obtenim els arxius descriptors per a cada tipus d'event. Per obtindre les metadades tenim 4 arxius anomenats: Datasets, Vocabulary, Bof i TF-IDF. Aquest últim a l'hora d'executar el nostre codi no l'hem utilitzat ja que no creiem que el nostre resultat millores (l'arxiu .txt contenia tot 'NonEvent')

-Per la part de classificació, execitant els arxius obtenim els resultats de les metadades. Per crear un arxiu amb el format evet_type + #tags de cada imatge implementem 4 funcions anomenades Models, Annotation, Ontology i Detector. 

-Per últim, obrint l'"Avaluador.py", executem l'arxiu canviant el directori. El sistema d'avaluació usat per aquest projecte retorna la Presició, Record, Accuracy i F-score. El codi mostra la informació d'una manera visual a través de gràfiques quan s'executa. 
