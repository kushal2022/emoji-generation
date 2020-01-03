# emoji-generation
emoji generation based on facial features.


Steps:
1.run face_capture.py::generate the images file
    -  face_capture.py --emotion_name <emotion_name> --number_of_images <no_of_image>
    example::
         face_capture.py --emotion_name smile --number_of_images 500
  
2.run dataset_creator.py:: create python pickled file and will save it in the dataset folder.

3.run trainer.py:: training the model on the dataset and saving it.

4.run predictor.py:: using the trained model to make prediction.
