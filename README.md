# Fingerprint Recognition using Siamese Network
The purpose of this project is to train a One-Short Learning Siasmese Network to make it recognise the fingerprints of a user.

#### File Structure:-
 - fingerprint.ipynb
 - images/
    - p1/
        - 1.jpg
    - p2/
        - 2.jpg
    - p3/
        - 3.jpg
 - model/
    - model_test5.h5
 - processed_images/
    - x1.npy
    - x2.npy
    - y.npy
 - test_images/
    - 1.jpg
    - 2.jpg
 - README.md

#### Data:-
The data being fingerprints of a particular person is private to them. So, I have not included a dataset.
However, there is a sample image(thumb_edited.jpg you will find it in `images/p1/`) which can be used to understand what kind of image is expected.
The fingerprints should be clear and the image should only contain the finger, not any more details.

The folder structure defines how the data needs to recide for the working. The data/files in the folders are only placeholders.

The `images` folder should contain all the individual person's fingerprints separated in folders (`p1/, p2/, p3/`).

The `model` folder will store the model that will be trained.

The `processed_images` folder will store the processed images in the form of numpy arrays.

The `test_images` folder will contain the images used to test your model.

The file `fingerprint.ipynb` is the python notebook where the code resides which is to be executed.

#### Implementation:-
Make sure to setup your data in the particular format and folder structure.
You can then execute the cells in `fingerprint.ipynb`.

#### Reference:-
My code is build upon the reference code from [here](https://github.com/shubham0204/Face_Recognition_with_TF)
