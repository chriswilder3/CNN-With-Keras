# CNN with Keras
## Series of notebooks containing the CNN experiments, notes and mini projects 

*Concepts Discussed*

- Kaggle dataset working in Colab/ local jupyter environments
- Preprocessing :
    - Loading huge image dataset in batches using 
    ```
        image_dataset_from_directory(main_directory, labels='inferred')
    ```
    - Data augmentation and batch generation both using
    ```
        tensorflow.keras.preprocessing.image's  ImageDataGenerator()
    ```
- Configure the dataset for performance using **Dataset.Cache** and **Dataset.prefetch**
- Standardize datasets with **layers.Rescaling**
- Custom augmentation with keras. Ex : **layers.RandomFlip**
- Dropout and Regularization
- CNN architecture building
- Model training
- Results & metrics visualization and analysis
- Inference ie, test on new data
- Using TensorFlow Lite
- Transfer Learning
- Fine Tuning
