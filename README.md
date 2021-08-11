# OCULAR-DISEASE-RECOGNITION

## Description
Eye defects in particular age-related eye defects is on the rise and this places burden on the health sector via the inaccessibility and unavailability of skilled professionals who can assist with their early diagnosis. The purpose of this model is to ease the detection of these eye disorder, enablin early detection and also providing a source of assisted information to healthcare practitioners who can then make use of the information provided by the model.

## Dataset
Dataset used comprises of over 9000 images obtained from this Kaggle dataset - https://www.kaggle.com/andrewmvd/ocular-disease-recognition-odir5k comprising fundus images of the normal eye and those of patients suffering from cataract, glaucoma and forms of diabetic neuropathy.

## Training, Testing and Performance Metrics
The model was run on 20 epochs with a performance of 97% training accuracy with a 87% validation accuracy. It was observed that this model displayed high precision with new data and fairly high recall too although this can be attributed to the choice of loss function being used (cross entropy) as it corrected false positives ignoring false negatives

![cm](https://user-images.githubusercontent.com/40724187/129103554-b954b608-a73c-483a-8082-329cdec643a8.png)

