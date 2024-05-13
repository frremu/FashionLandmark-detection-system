# Fashion Landmark Detection Model Using VGG-16

## Introduction

The Fashion Landmark Detection System is a deep learning-based solution aimed at boosting productivity within the fashion sector. The system's primary objective is to accurately identify critical body landmarks for garment fitting through advanced computer vision techniques. By leveraging state-of-the-art methodologies, the system enables precise alignment of virtual garments with the user's unique physique, thereby enhancing the overall shopping experience and reducing returns due to ill-fitting clothing.

![image](https://github.com/frremu/FashionLandmark-detection-system/assets/107552577/768be9e2-eec4-491a-9efb-3ca0493b34a0)


## Objectives

The key objectives of the project are as follows:

- Develop a deep learning model for fashion landmark detection.
- Collect and preprocess a comprehensive dataset of fashion images with annotated body landmarks.
- Train the deep learning model using convolutional neural networks (CNNs) and state-of-the-art techniques.
- Implement feature extraction techniques to enhance the model's ability to identify essential body landmarks accurately.
- Fine-tune the model to improve accuracy and robustness in different poses and clothing styles.

## Methodology

### Data Collection

A diverse dataset of fashion images was collected from various sources, including Mannat Clothing, Salitex, For you by Warisha, Luxeurs, Silayi prets, Shomi (a marketplace), and Kaggle datasets. The dataset comprises 2400 images categorized into trousers, shirts, and complete outfits to capture diverse styles prevalent in Eastern fashion. Special attention was given to including variations in clothing styles, sleeves, neck designs, and poses.

### Data Cleaning

The collected dataset underwent meticulous cleaning to ensure its quality and reliability. Irrelevant images, including logos and catalogues, were manually removed, and duplicates were eliminated for a cleaner dataset. Images with poor resolution were filtered out to ensure clarity and consistency in the dataset.

### Data Annotation

The dataset was annotated using the VGG Image Annotator tool, with a specific focus on annotating critical body landmarks, joints, and contours for virtual fitting and accuracy. A total of 20 landmarks were annotated on trousers, 20 on shirts, and 34 on complete outfits to capture detailed points for accurate garment placement.

![image](https://github.com/frremu/FashionLandmark-detection-system/assets/107552577/56253fa7-80c9-40fb-82fd-fd97f6832763)


### Data Pre-processing

The annotated data underwent pre-processing, including resizing images to a standardized 244x244 dimensions for efficient model training. Landmark coordinates were normalized to ensure consistent scale and positioning, and both images and landmarks were converted into arrays for model input. Consistent and standardized pre-processing procedures were followed to ensure uniformity and reliability in model training.

### Model Development

A modified version of the VGG-16 architecture was utilized for fashion landmark detection. The customized architecture includes additional layers such as flattening, dense, and output layers specifically designed for predicting landmark coordinates. The model was trained using various optimization algorithms such as Adam, Nadam, and RMSprop, and its performance was evaluated based on testing loss metrics including Mean Squared Error (MSE) and Mean Absolute Error (MAE).

## Results

The Fashion Landmark Detection System demonstrates promising results in accurately identifying critical body landmarks for garment fitting. The model achieves high precision and accuracy in landmark localization, thereby facilitating flawless alignment of virtual garments with the user's physique. Performance evaluation metrics such as MSE and MAE indicate the effectiveness of the model in capturing detailed points for accurate garment placement.

![image](https://github.com/frremu/FashionLandmark-detection-system/assets/107552577/98c09547-f7ed-443e-928f-ad982d63f0e8)

![image](https://github.com/frremu/FashionLandmark-detection-system/assets/107552577/12b75ddd-5dcf-46d2-b80f-4a86152ad337)


## Conclusion

The Fashion Landmark Detection System represents a significant advancement in the field of fashion technology, offering a reliable solution for precise garment fitting and virtual try-on experiences. By leveraging deep learning techniques and advanced computer vision methodologies, the system enhances productivity within the fashion sector and improves the overall shopping experience for consumers. Further refinements and optimizations can be made to enhance the model's accuracy and robustness in diverse clothing styles and poses.

![image](https://github.com/frremu/FashionLandmark-detection-system/assets/107552577/aea5ede8-b2ae-436b-970e-3864febd92d7)

