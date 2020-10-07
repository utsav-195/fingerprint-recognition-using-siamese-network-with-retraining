# Fingerprint Recognition using Siamese Network
The purpose of this project is to train a One-Short Learning Siasmese Network to make it recognise the fingerprints of a user.
This project has two implementations one using Tensorflow and Keras, other using PyTorch.

#### File Structure:-
 - fingerprint.ipynb
 - images/
    - p1/
        - thumb_edited.jpg
    - p2/
        - thumb_edited.jpg
    - p3/
        - thumb_edited.jpg
 - model/
    - model_test5.h5
 - processed_images/
    - x1.npy
    - x2.npy
    - y.npy
 - test_images/
    - thumb_edited.jpg
 - README.md

#### Data:-
The data being fingerprints of a particular person is private to them. So, I have not included a dataset.
But the folder structure defines how the data needs to recide for the working. The data/files in the folders are only placeholders.

The `images` folder should contain all the individual person's fingerprints separated in folders (`p1/, p2/, p3/`). Each folder must contain 1 fingerprint images of a separate person. An example of how the image should look like is present in the folders.

The `model` folder will store the model that will be trained.

The `processed_images` folder will store the processed images in the form of numpy arrays.

The `test_images` folder will contain the images used to test your model.

The file `fingerprint.ipynb` is the python notebook where the code resides which is to be executed.

#### Implementation:-
Make sure to setup your data in the particular format and folder structure.
The notebook has comments indicating what each cell does.
You can then execute the cells in `fingerprint.ipynb` to see how everything works.

The notebook has 3 part, the first part is the implementation using Tensforflow and Keras.
The second part is the code to add a new user to your system.
The third part is the model implemented using PyTorch.

#### Result:-
![Result](results.PNG?raw=true)