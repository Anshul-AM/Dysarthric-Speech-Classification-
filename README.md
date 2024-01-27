# Dysarthric-Speech-Classification
Dysarthria, a speech disorder, is often overlooked by current automated recognition systems. This model introduces an accurate automated solution using glottal and acoustic features to classify dysarthric voices, significantly improving upon traditional methods.

PURPOSE OF THE PROJECT:

1. Evaluate the performance separately on words, non-words and sentences.
2. Explore the effectiveness of glottal parameters individually and in combination with openSMILE acoustic parameters.
3. Use of recent efficient GIF method, QCP for estimating glottal parameters.
4. To identify the presence of dysarthria.
5. To evaluate the performance separately on non-words, words and sentences extracted from glottal signal.


The architecture diagram, provides an outline of the modules present in the model. It comprises of speech utterances provided by the database that is further manipulated to extract glottal features using QCP and two sets of acoustic features using openSMILE toolkit. Sequential forward feature selection is employed to reduce
the feature set size. SVM is then used on individual or combination of features to provide the classification result.

![image](https://github.com/Anshul-AM/Dysarthric-Speech-Classification-/assets/150291680/eb44cf0f-ebb0-4edd-b2ea-768970fe8809)
