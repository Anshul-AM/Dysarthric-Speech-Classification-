# Dysarthric-Speech-Classification
Dysarthria, a speech disorder, is often overlooked by current automated recognition systems. This model introduces an accurate automated solution using glottal and acoustic features to classify dysarthric voices, significantly improving upon traditional methods.

Database:
The database used to make dysarthric speech classifier is the torgo database [14]. The torgo database comprises of voice specimen of healthy as well as people suffering from dysarthria. The database consists of voice specimen of fourteen individuals which is divided into two batches one suffering from dysarthria and the other not suffering from it(healthy). Each batch has four male individuals and three female individuals respectively. The individuals who recorded the voice specimen have ages ranging from sixteen to fifty years.
Voice signals are stored in three formats:
Sentences: Are further divided into two segments restricted and unrestricted.
Words: These are helpful to analyze sentences which do not have a definite start or endpoint.
Non words: There are nine to eight samples of each individual suffering from dysarthria.

The architecture diagram, provides an outline of the modules present in the model. It comprises of speech utterances provided by the database that is further manipulated to extract glottal features using QCP and two sets of acoustic features using openSMILE toolkit. Sequential forward feature selection is employed to reduce
the feature set size. SVM is then used on individual or combination of features to provide the classification result.

![image](https://github.com/Anshul-AM/Dysarthric-Speech-Classification-/assets/150291680/eb44cf0f-ebb0-4edd-b2ea-768970fe8809)
