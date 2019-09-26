# MultioutputClassification
It is simply a generalization of multilabel classification where each label can be multiclass (i.e., it can have more than two possible
values).


To illustrate this,Suppose, let’s build a system that removes noise from images. It will take as input a noisy digit image, and 
it will (hopefully) output a clean digit image, represented as an array of pixel intensities, just like the MNIST images. 
Notice that the classifier’s output is multilabel (one label per pixel) and each label can have multiple 
values (pixel intensity ranges from 0 to 255). It is thus an example of a multioutput classification system.


The line between classification and regression is sometimes blurry, such as in this example. Arguably, predicting pixel intensity is more
akin to regression than to classification. Moreover, multioutput systems are not limited to classification tasks; you could even have 
a system that outputs multiple labels per instance, including both class labels and value labels.
