# Face-recogition
Face Recognition with K -nearest neighbours.
The knn classifier is first trained on a set of labeled (known) faces and can then predict the person
in an unknown image by finding the k most similar faces (images with closet face-features under euclidean distance)
in its training set, and performing a majority vote (possibly weighted) on their label.



1. Prepare a set of images of the known people to be recognized. Organize the images in a single directory
   with a sub-directory for each known person.
2. Call the train function with the appropriate parameters. Pass in the model_save_path if you
   want to save the model to disk so you can re-use the model without having to re-train it.
3. Call predict and pass in your trained model to recognize the people in an unknown image.




