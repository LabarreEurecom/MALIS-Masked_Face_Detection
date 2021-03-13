# MALIS-Masked_Face_Detection

<ins>*Machine Learning Project in the first semester of the scholar year 2020-2021 in EURECOM.*</ins>

*The exact title of the project is* : 

          Detection of mask wearing during the Covid-19 health crisis

Source for the data : https://github.com/cabani/MaskedFace-Net - Images of size 1024x1024

For the rest, I will note **MWD** for **Mask Wear Detection**.

<ins>*Explanation of some notations*</ins>:

For repositories:
- **Individual_tests_internet**: Images of ppl (1024x1024) wearing any kind of mask taken from the internet to test models. 
- **Myself**: Images taken by myself to test the semi-dynamic model.
- **Surgical_face_masks_internet**: Images of ppl (1024x1024) wearing surgical mask taken from the internet to test models.
- **Um_1000**: Folder containing 1,000 images of unmasked ppl.
- **Unc_Chin_200**: Folder containing 200 images of ppl masked with uncovered chin.
- **Unc_Nose_200**: Folder containing 200 images of ppl masked with uncovered nose.
- **Unc_Nose_and_Mouth_200**: Folder containing 200 images of ppl masked with uncovered nose and mouth.
- **Wm_1000**: Folder containing 1,000 images of (worn) mask ppl.

For ipynbs:
- **MWD-Logistic_Regression**: Model to detect whether a person, in a RGB image, is wearing a surgical mask or not.
- **MWD-Logistic_Regression-Grayscale**: Model to detect whether a person, in a grayscale image, is wearing a surgical mask or not.
- **MWD-Logistic_Regression-5_labels**: Model to detect whether a person, in a RGB image, is wearing a surgical mask or not and if the person is wearing correctly it or not. 
- **MWD-Semi_Dynamic**: Model to detect whether a person, in a RGB image taken by a running camera, is wearing a surgical mask or not.

Indeed, I always talk about surgical mask because my training, testing and validation datasets are composed of ppl wearing a surgical mask (when they wear it one).
