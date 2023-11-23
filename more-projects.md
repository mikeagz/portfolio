[⬅️ back](./)

### 🌽 Autonomous Navigation Vision System 🌽 (2023)

An autonomous navigation system was developed for agricultural robots based on the tracking of corn rows through **image segmentation** with deep learning models. The system was implemented on **Jetson Xavier** and Arduino devices. Languages and frameworks such as **Python**, **Pytorch** and **Tensorflow** were used.

![Row Detection](/assets/img/row_detect.png)

### 💵 Adult Income 💵 (2023)
An analysis of the classic Adult dataset where data **cleaning** and **preprocessing** techniques were applied, as well as **modeling** and **deployment** of a binary classifier. The following tools were used:
- Sklearn
- Streamlit
- FeatureEngine
- ImbalancedLearn
- Pandas
- Plotly

<p align="center">
   <img width=500 src="https://github.com/mikeagz/portfolio/blob/main/assets/img/app_view.png?raw=true" alt="Demo"/>
</p>

### 📈 Tomato market analysis 📈 (2023)
The objective of this project was to analyze the flow of tomato prices between national markets. The database was obtained through the SNIIM system (Mexico). This project completed the activities:
- Data minning
- Data cleaning 
- Exploratory Data Analysis

Librarys and tools:
- Scrapy
- Sklearn
- Pandas
- Plotly
- SQL

<p align="center">
   <img width=450 src="https://github.com/mikeagz/portfolio/blob/main/assets/img/tomato_market.jpg?raw=true" alt="Demo"/>
</p>

### 🕺🏽Character Classifier 🕺🏽(2022)
The main task is to classify Simpsons characters using a **convolutional neural network**, the activities include:
- Data acquisition
- Exploratory analysis of the data set
- Preprocessing and manipulation 
- Modeling
- Evaluation of the model.

Highlights:
- Preprocessing contemplates centering and filling operations since the exploratory analysis revealed images with different dimensions and aspect ratio.
- The transformed images were stored on disk using **TFRecords** to test their efficiency in manipulation and consumption in the training process.
- The convolutional network model was trained in TensorFlow using a custom class inherited from tf.module with weight initializers subject to a **uniform lecun** distribution.
- Sklearn was useful for model evaluation with metrics such as **confusion matrix**, **precision**, recall and f1.

![Simpson](assets/img/simpson.png)

### 🍔 Fast Food Classifier 🍔(2022)
In this project we have classified different fast foods and different representations (commercial, amateur photos, professional photos, etc). The activities include:
- Preprocessing and manipulation
- Modeling
- Model evaluation

Aspects to be highlighted:
- The **pre-trained EfficientNet B0** model was chosen as the base model for the classifier.
- The **cosine annealed decay** and reset algorithm was used for the learning rate in order to obtain improvements in the neural network weight optimization process.

<p align="center">
   <img width=450 src="https://github.com/mikeagz/portfolio/blob/main/assets/img/fastfood.jpg?raw=true" alt="Demo"/>
</p>

### 🌏 Research on World Models 🌏 (2021-2023)
Master thesis that improves the performance of world-model based agents by reducing the number of parameters in appropriate models such as **PCA** and **VAE**. The project was developed in **Python** and **Tensorflow**.

Aspects to be highlighted:
- To facilitate the inference of the proposed models and experimentation, a local deployment with `serving_default` of TensorFlow was chosen.
- **Weights & Biases** was used to track experiments and model performance. 
- An optimization based on **evolutionary algorithms** was chosen instead of gradient-based algorithms. 

<p align="center">
   <img width=450 src="https://github.com/mikeagz/portfolio/blob/main/assets/img/worldModel.jpg?raw=true" alt="Demo"/>
</p>

### 🤖 Agricultural robot for spraying 🤖 (2020)
Agricultural robot prototype for monitoring and spraying tasks in tomato greenhouses. The project covered the mechanical design and development of control systems at the functional prototype level. Solidworks, **Matlab** and Labview were used.

Aspects to be highlighted:

- The robot was designed from scratch and validated with specialized software to withstand the real conditions of agricultural environments.
- The control system was based on classical algorithms such as PID and PD for motor control by means of system identification and controller design.
- The power electronics were chosen to be modular in order to facilitate repair or scaling up.
- The development boards were programmed in **C++ language**.
