# Problem Statement:-
Melanoma is a fatal disease, which needs to be diagnosed and cured at an earlier/benign stage. Provided a set of images of the lesions for a given patient, we have to detect the stage (Benign or Malignant) of melanoma. If we are successful in detecting melanoma at the Benign stage using the set of images for a person, we can help save lives.

# Brief Description: 
Skin cancer is the most prevalent type of cancer. Melanoma, specifically, is responsible for 75% of skin cancer deaths, despite being the least common skin cancer. As with other cancers, early and accurate detection—potentially aided by data science—can make treatment more effective. 
Currently, dermatologists evaluate every one of a patient's moles to identify outlier lesions or “ugly ducklings” that are most likely to be melanoma. Existing AI approaches have not adequately considered this clinical frame of reference. Dermatologists could enhance their diagnostic accuracy if detection algorithms take into account “contextual” images within the same patient to determine which images represent a melanoma. If successful, classifiers would be more accurate and could better support dermatological clinic work.
In order to be able to detect melanoma from the images we got, we have 2 criterias:
1) ABCDE criteria:-
# A is for Asymmetrical shapes – Moles with irregular shapes or two different looking sides
# B is for irregular Border – Moles with irregular, notched or scalloped appearing borders
# C is for changes in Color – Moles or growths with many colors or uneven colors
# D is for Diameter – New growth in moles larger than ¼ inch.
# E is for Evolving – Moles that change over time in size, color or shape. Moles that itch or bleed.

2) Ugly Ducklings

In this project, we will identify melanoma in images of skin lesions. In particular, we will use images within the same patient and determine which are likely to represent a melanoma. Using patient-level contextual information may help the development of image analysis tools, which could better support clinical dermatologists.
Melanoma is a deadly disease, but if caught early, most melanomas can be cured with minor surgery. Image analysis tools that automate the diagnosis of melanoma will improve dermatologists' diagnostic accuracy. Better detection of melanoma has the opportunity to positively impact millions of people.

# Link for the Research Paper - https://arxiv.org/abs/2008.07360
# Link for the image dataset - https://www.kaggle.com/c/siim-isic-melanoma-classification/data
The dataset represents 2,056 patients from three continents with an average of 16 lesions per patient, consisting of 33,126 dermoscopic images and 584 histopathologically
confirmed melanomas compared with benign melanoma mimickers.
