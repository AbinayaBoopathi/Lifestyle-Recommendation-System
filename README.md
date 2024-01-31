# Lifestyle-Recommendation-System
We Developed the Life Style Recommendation System. This will give the suggetion based on user age, blood pressure, stress level, heart rate and activity level. This project is developed using Machine Learning model and Gradio User Interface.

The primary goal of our project is to revolutionize personal health monitoring through the development of a comprehensive mobile application. By seamlessly integrating vital sign and activity inputs, leveraging machine learning algorithms such as Logistic Regression and Random Forest, and utilizing Gradio for an intuitive user interface, our system aims to empower users with personalized insights into their overall well-being. The ultimate objective is to assist users in making informed decisions about their lifestyle and health habits, fostering a positive impact on their health journey.

##Table of contents

Objectives
oneAPI
oneAPI Optimization
Proposed System
Key Components
Workflow
Output
Video Explanation
Setup
Results and Discussion

##Introduction

In today's fast-paced world, health awareness and proactive well-being management have become increasingly important. Our project introduces a novel approach to health monitoring, utilizing a mobile application that collects and analyzes various vital signs and activities. This transformative tool goes beyond mere data collection, providing users with tailored suggestions and valuable insights into their overall body condition. The integration of machine learning algorithms elevates the system's capabilities, enabling it to offer personalized recommendations for improved lifestyle and health choices.

##Objectives

Gather a diverse range of health-related inputs, including vital signs (heart rate, blood pressure, fall detection, calories) and lifestyle details (gender, age, occupation, sleep duration, sleep quality, physical activity level, stress levels, BMI category, daily steps, presence or absence of sleep disorders).Implement advanced machine learning algorithms, such as Logistic Regression and Random Forest, to analyze the collected data and derive meaningful insights into the user's well-being.Transform user health journeys by providing personalized, actionable suggestions based on the analyzed data, aiming to positively impact lifestyle and health habits.

 ##oneAPI

To ensure the scalability and adaptability of our health monitoring system, we leverage oneAPI, a unified programming model. This allows us to efficiently harness the computing power of various architectures, providing a seamless user experience across different devices.

![image](https://github.com/AbinayaBoopathi/Lifestyle-Recommendation-System/assets/114607378/5d2ac863-d1d4-46ff-ab43-0ca43414d933)

##oneAPI Optimization

Optimizing our system using oneAPI involves enhancing performance through parallel processing and hardware acceleration. By leveraging oneAPI, we ensure that our health monitoring application is not only efficient but also adaptable to different computing environments.


##Proposed Systems

An intuitive platform that serves as the user interface, facilitating the input of health data and presenting personalized insights. Responsible for gathering a comprehensive set of health-related inputs, ensuring a holistic understanding of the user's well-being. Utilizes Logistic Regression and Random Forest algorithms to analyze the collected data, generating valuable insights and recommendations. Incorporates Gradio to create a user-friendly interface within the mobile application, making health monitoring accessible and engaging.

##Flowchart

![WhatsApp Image 2024-01-31 at 14 57 01_7b9ec283](https://github.com/AbinayaBoopathi/Lifestyle-Recommendation-System/assets/114607378/3abccf9f-0a1d-41de-9603-65dd7f1e5648)


##Key Components

###Data Collection Module:

A labled dataset containing age,stress level,activity_level and blood_pressure is used for getting the life style suggetion.Gathers a wide range of health data, ensuring a holistic and detailed analysis.

###Machine Learning Module:

Implements advanced algorithms to derive insights from the collected data, providing valuable information for user well-being.

###Gradio User Interface:

Enhances user experience by providing an intuitive platform for inputting health data and receiving personalized suggestions.


##Workflow:

###Data Input:

Users input their health data through the user-friendly Gradio interface on the mobile application.

###Training Phase:

The SVM model is trained using the labeled dataset, learning the patterns and characteristics of genuine and fake reviews.
Feature extraction methods are applied to represent the reviews in a format suitable for SVM training.

###Integration with Gradio:

Gradio interface is implemented to take user input in the form of a product review.
The input is processed and fed into the trained SVM model for classification.
The model's output, indicating whether the review is genuine or fake, is displayed to the user.

###User Interaction:

Users interact with the Gradio interface by inputting product reviews of their choice.
The interface provides real-time feedback, instantly displaying the model's classification results.


#Output:

##Gradio Interface

Enhances user experience by providing an intuitive platform for inputting health data and receiving personalized suggestions.




###Health Suggetion:
Users receive a personalized health report within the mobile application. The output includes visualizations, insights, and tailored suggestions based on their unique health profile.

##Video Explanation

For a comprehensive understanding of the system, we provide a detailed video explanation. This video walks users through the features, functionalities, and benefits of our health monitoring application, showcasing its transformative capabilities.




##Results and Discussion

Upon implementation, our system has demonstrated its effectiveness in providing personalized health insights and suggestions. User feedback and ongoing discussions contribute to refining the system, ensuring it remains a valuable companion on each user's health journey. The results and discussions will continue to shape the system's evolution, making it an even more impactful tool for health monitoring and lifestyle improvement.















