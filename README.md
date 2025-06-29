# Deep Learning Model Deployment for Android Application

# **Motivation:**

Due to the COVID-19 pandemic, safety measures such as wearing masks and maintaining social distance have been implemented to prevent the spread of the virus. As a result, people wear masks wherever they go, making it difficult to see their faces and recognize their identities. To address this challenge, deep learning models can be used to predict or reconstruct the face of a person behind a mask.

For deep learning models to solve real-world problems, they must be deployed effectively. Model deployment is just as important as model development. The primary goal of building a deep learning model is to solve a practical problem—and this can only be achieved when the model is in production and actively in use.

It is essential to regularly train and update the model, especially when dealing with anonymous or variable data. Any new model should be thoroughly tested before replacing the existing one in production. Once deployed, the model can be integrated into mobile applications to enable real-time usage and accessibility.

# **Objective:**

The objective of this project is to enable real-time face reconstruction from masked images using a deep learning model integrated within an Android application. User images captured in the app are uploaded to the cloud, where a pre-trained deep learning model—deployed to FirebaseML—processes them. The remote model takes an input image of a person wearing a face mask and generates an output image predicting the face without the mask. By leveraging FirebaseML, the Android app can access this model for real-time inference, ensuring scalable and efficient on-device predictions.
