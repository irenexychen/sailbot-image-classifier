# sailbot-image-classifier
Image classifier implementing Tensorflow's Inception-v2 model, classifies sailboats, buoys and water, to participate in the International Robotic Sailing Regatta 2018. 

Dataset included. To run, download the inception-v2 2015 model.



Snapshot of training process:

![training](https://raw.githubusercontent.com/PotentialOnWings/sailbot-image-classifier/master/training.png)



Snapshot of result:

![running tests](https://raw.githubusercontent.com/PotentialOnWings/sailbot-image-classifier/master/runningtests.png)

(Reference to test_images directory) Runs pictures with single subject with over 99% of confidence. Runs pictures with multiple objects as subject with over 90% confidence for the main subject, and is able to detect the secondary object as well.   
