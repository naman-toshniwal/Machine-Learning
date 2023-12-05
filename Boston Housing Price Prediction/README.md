## Boston Housing Price Prediction

Using the Boston Housing Dataset from UCI Machine Learning Data Repository, we have created a machine learning model which predicts the price of the real estate in the area on basis of the available parameters. 

The dataset consisted of following parameters which later resulted to the value of the price of the real estate, namely 'MEDV' which is calculated in thousands.
![image](https://github.com/naman-toshniwal/Machine-Learning/assets/109726889/290ef2c1-de09-4b17-a559-a9da86a04d0a)

We understood the entire data scenario and came to certain conclusions:
![image](https://github.com/naman-toshniwal/Machine-Learning/assets/109726889/0190036f-5483-4289-852d-e16d07513d4e)

We looked for correlations among the important parameters and found certain results:
![image](https://github.com/naman-toshniwal/Machine-Learning/assets/109726889/7aff7f65-3149-4826-bf1a-00338cfeae3c)
![image](https://github.com/naman-toshniwal/Machine-Learning/assets/109726889/2d3cc276-6c16-429b-818b-47a7e6b22184)
![image](https://github.com/naman-toshniwal/Machine-Learning/assets/109726889/d26cd375-c1cc-4209-981d-d299e5d34292)

We finally created a pipeline and implemented the Random Forest Regressor and found certain results:
Scores:  [2.76376402 2.70337018 4.36721533 2.29349612 3.50345822 2.66559903 4.75851699 3.37924755 3.44871916 3.17262874]
Mean:  3.305601532666281
Standard Deviation:  0.7355918465245224
