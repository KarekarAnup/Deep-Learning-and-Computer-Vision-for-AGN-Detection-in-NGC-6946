# Deep-Learning-and-Computer-Vision-for-AGN-Detection-in-NGC-6946
### Project Description:
This project aims to leverage deep learning and computer vision techniques to detect Active Galactic Nuclei (AGN) within NGC 6946, also known as the "Fireworks Galaxy." NGC 6946 is a prominent spiral galaxy with high supernova activity and dynamic stellar formation, making it an intriguing subject for AGN study. 
The project will involve collecting high-resolution images of NGC 6946 from public astronomical databases, followed by preprocessing tasks such as noise reduction, normalization, and enhancement to improve image quality. Using advanced computer vision methods, we will extract features indicative of AGN, including brightness, spectral characteristics, and morphological features.
A Convolutional Neural Network (CNN) will be developed and trained using a labeled dataset of galaxies with known AGN. The model's performance will be evaluated using metrics such as accuracy, precision, recall, and F1-score, and validated against existing AGN catalogs. 
Through this approach, the project aims to create a robust model capable of accurately detecting AGN within NGC 6946, contributing to the understanding of the galaxy’s dynamics and central black hole activities. This research will enhance our knowledge of AGN's role in galactic evolution and provide a foundation for further studies in astrophysics.

_____________________________________________________________________________________________________________________________

### Introduction:
NGC 6946, also known as the "Fireworks Galaxy," is a prominent spiral galaxy located in the constellation Cepheus. It is renowned for its high supernova activity and dynamic stellar formation. Detecting Active Galactic Nuclei (AGN) in such a galaxy can provide valuable insights into the galaxy’s evolution and central black hole activities.

### Objectives:
1. **Image Acquisition and Preprocessing:**
   - Collect high-resolution images of NGC 6946 from public astronomical databases (e.g., Hubble Space Telescope, Sloan Digital Sky Survey).
   - Perform preprocessing tasks such as noise reduction, normalization, and enhancement to improve image quality.

2. **Feature Extraction:**
   - Utilize computer vision techniques to extract relevant features indicative of AGN, such as brightness, spectral characteristics, and morphological features.

3. **Deep Learning Model Development:**
   - Develop a deep learning model (e.g., Convolutional Neural Network) to classify and detect AGN within NGC 6946.
   - Train the model using a labeled dataset of galaxies with known AGN.

4. **Evaluation and Validation:**
   - Evaluate the model’s performance using metrics such as accuracy, precision, recall, and F1-score.
   - Validate the model with a separate test set of images and cross-check detections with existing AGN catalogs.

### Methodology:
1. **Data Collection:**
   - Download and compile images of NGC 6946 from astronomical databases.
   - Collect metadata and labels for training, including confirmed AGN presence.

2. **Image Preprocessing:**
   - Apply filters to reduce noise and enhance image clarity.
   - Normalize images to standardize pixel values.
   - Segment the galaxy to focus on regions of interest.

3. **Feature Extraction:**
   - Use image processing techniques (e.g., edge detection, texture analysis) to identify potential AGN regions.
   - Extract spectral features using multi-band images to capture distinct AGN signatures.

4. **Deep Learning Approach:**
   - Design a Convolutional Neural Network (CNN) tailored for AGN detection.
   - Train the CNN using a diverse dataset of galaxy images with annotated AGN.
   - Implement data augmentation techniques to enhance model robustness.

5. **Model Training and Optimization:**
   - Use a combination of labeled training data and unsupervised learning for semi-supervised refinement.
   - Optimize model hyperparameters through cross-validation.

6. **Evaluation:**
   - Test the model on a validation set and compare results against established AGN catalogs.
   - Perform statistical analysis to assess model performance and reliability.

### Expected Outcomes:
- A robust, trained deep learning model capable of detecting AGN in NGC 6946.
- A comprehensive analysis of detected AGN regions within NGC 6946.
- Enhanced understanding of the AGN activity and its implications on the galaxy's dynamics.

### Tools and Technologies:
- **Programming Languages:** Python, R
- **Libraries:** TensorFlow, Keras, OpenCV, Scikit-learn
- **Datasets:** Hubble Space Telescope, Sloan Digital Sky Survey
- **Software:** Jupyter Notebook, MATLAB, Astropy

### Timeline:
1. **Month 1-2:** Data collection and preprocessing.
2. **Month 3-4:** Feature extraction and initial model development.
3. **Month 5-6:** Model training and optimization.
4. **Month 7-8:** Evaluation and validation.
5. **Month 9:** Final analysis and report preparation.

### Conclusion:
This project aims to leverage the power of computer vision and deep learning to enhance the detection of Active Galactic Nuclei in NGC 6946. By developing a robust model, the project will contribute to the broader understanding of galaxy dynamics and the role of AGN in galactic evolution.

---

### References:
- [Hubble Space Telescope Data Archive](https://archive.stsci.edu/hst/)
- [Sloan Digital Sky Survey](https://www.sdss.org/)
- [Astropy](https://www.astropy.org/)
- [TensorFlow](https://www.tensorflow.org/)
- [OpenCV](https://opencv.org/)
