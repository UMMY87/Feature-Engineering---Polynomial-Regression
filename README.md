# Feature-Engineering---Polynomial-Regression
This code snippet illustrates the impact of feature engineering and normalization on the performance of a linear regression model. Initially, a simple linear regression model is trained on the dataset without any feature engineering. The plot shows the actual target values and the predictions made by the model. However, the model struggles to capture the non-linear relationship between the input feature and the target.

To address this limitation, feature engineering techniques are applied to the input data. First, the input feature is squared, creating a quadratic relationship between the input and the target. The model is then retrained on this engineered feature, resulting in improved predictions that better fit the data.

Further enhancing the feature set, additional features like cubic terms are introduced. The resulting model becomes more flexible, capturing even more complex relationships between the input features and the target variable. The plots visualize these relationships, demonstrating how the model adapts to the increasingly complex data patterns.

To ensure robustness and stability in training, feature normalization is applied. Z-score normalization is performed on the input features to bring them to a common scale, preventing numerical instabilities during gradient descent optimization. The peak-to-peak range of the features before and after normalization is compared to verify the effectiveness of normalization in standardizing the feature scales.

Finally, the model is trained on the normalized feature set, resulting in a more stable and efficient optimization process. The predictions made by this model exhibit improved accuracy and generalization, as demonstrated by the plotted actual versus predicted values. Overall, this code showcases the importance of feature engineering and normalization techniques in enhancing the performance of linear regression models on non-linear datasets.
## Plot of No Feature Engineering
![No Feature Engineering plot](https://github.com/UMMY87/Multiple-Variables-in-Linear-Regression/assets/117314436/9f96e6b1-3345-47a8-a672-0155e9264969)
## Plot of Added x^2 feature
![Added x^2 feature plot](https://github.com/UMMY87/Multiple-Variables-in-Linear-Regression/assets/117314436/f111376b-a6ab-47a9-8a7b-bd7c5ac7949b)
## Plot of x, x^2, x^3 features
![Plot of x, x^2, x^3 features](https://github.com/UMMY87/Multiple-Variables-in-Linear-Regression/assets/117314436/87c1147b-5bb3-43e1-80d0-90edfc0607fe)
## Plot of x, x^2, X^3 on y
![Plot of x, x^2, X^3 on y](https://github.com/UMMY87/Multiple-Variables-in-Linear-Regression/assets/117314436/19d3180d-fb8b-4145-bbb6-7e532d045840)
## Plot of Normalized x, x^2, x^3 feature
![Plot of Normalized x, x^2, x^3 feature](https://github.com/UMMY87/Multiple-Variables-in-Linear-Regression/assets/117314436/0ef21ee9-b010-4a40-98fa-70aab838d605)
