# Diabetic-Retinopathy Using Deep Learning Techniques
Diabetic Retinopathy is a disease that damages the eyes and is caused by a consequence of diabetes. If blood sugar levels aren’t controlled for an extended period of time, the disease can develop.Medical imaging plays a very crucial role in a variety of medical issues and at all major levels of health issues and can be used to
identify a variety of common eye illnesses. Ophthalmologists’ manual Diabetic Retinopathy diagnostic procedure is time-consuming, requires more work, costly, and might result in misdiagnosis. Basing on the vision like having trouble in reading distant objects or seeing distant objects, blindness or any other changes may happen in eye retina that affects diabetes. Diabetic retinopathy is one of the most frequent eye illnesses, affecting mostly diabetics. This model using deep learning convolution neural networks can assist the opthmologists by providing clear images of the retina, and classifying them based on severity. In this work, From the presented retinal fundus pictures, we utilized the Res-Block model to classify and diagnose diabetic retinopathy.
# Flow Chart
![image](https://user-images.githubusercontent.com/79081616/176475913-865e6f88-94c0-41f1-bf3d-0ce988fbc48a.png)
# Algorithm
	1. Import all the necessary libraries

	2. Perform data exploration and data visualization.

		* visualize images for each class in the dataset

		* get the list of images in a given class.

		* check the number of images in each class in the training dataset.

	3. Perform data augmentation and create data generator.

		* shuffle the data and split it into training and testing

		* create run-time augmentation on training and test dataset

		* for training data generator, we add normalization, shear angle, zooming range and horizontal flip

		* for test data generator, we only normalize the data.

		* creating data generator for training, validation and test dataset.

	4. Convolutional neural networks (CNN) and residual blocks

	5. Build block based deep learning model

	6. Compile and train deep learning model

		* using early stopping to exit training if validation loss is not decreasing even after certain epochs (patience)

		* save the best model with lower validation loss

	7. Assess the performance of the trained model

		* Evaluate the performance of the model

		* Assigning label names to the corresponding indexes

		* Loading images and their predictions

		* Getting the test accuracy

		* Visualizing the results.

# Dataset
The dataset consists of 3553 color images belonging to 5 categories. Categories that are present in the data are No DR, Mild, Moderate, severe and proliferative.

# Outputs
![image](https://user-images.githubusercontent.com/79081616/176476871-4d6fa25d-57a1-458c-a87a-54e02a0ae19e.png)
![image](https://user-images.githubusercontent.com/79081616/176476976-525f5e98-9a6c-4964-8774-49587d41b17d.png)
![image](https://user-images.githubusercontent.com/79081616/176477112-f02d25d9-fecc-4be7-9ae6-3542a34640c9.png)
![image](https://user-images.githubusercontent.com/79081616/176478088-d9ff7098-5b15-4046-8ffa-0c8d894eae21.png)

# Results
In this model, From the presented retinal fundus pictures, we utilized the Res-Block model to classify as Mild, Moderate, No DR, Proliferative DR classes respectively and diagnose diabetic retinopathy we have obtained an accuracy of 92%.
![image](https://user-images.githubusercontent.com/79081616/176477314-d80d6643-2cff-42ad-ab96-f221b9707b2b.png)
![image](https://user-images.githubusercontent.com/79081616/176477382-a8b6a87b-c136-41fb-9932-52a536e8611a.png)

# Conclusion & Future Work
We directly placed the dataset from different sources like hospitals,physical diagnosis, localized patients. The input data is uploaded with corresponding structure format according to the hierarchies designed by medical expertise and physical diagnose professionals.
• The accuracy we achieve after training and testing the model is comparable. For more accurate findings, we’d want to expand our work by applying a variety of machine learning algorithms like as SHIFT, Deep Convolution Neural Network (DCNN), and others.
