# concert-price-prediction
This is my first real project in Machine Learning, and it's linear and polynomial regression using data from this repo: https://github.com/AinaFih/Concerts_Dataset-Project. It contains simulated concert data such as artists, genres, performances, and pricing. My model predicts ticket prices given input features mentioned above.

This project helped me learn about data manipulation and preprocessing with pandas, and the importance of encoding your data, e.g. transforming data with logarithmic functions for reduced variance and identifying potential exponential relationships in the data, one-hot-encoding for categorical features, cyclical encoding with trigonometric functions for dates.

I also learned about visualising data with matplotlib and identifying outliers in the data this way.

I learned about cross-validation and implemented it manually after learning about the theoretical concept for comparing performance of different models and finding the best 'alpha' for ridge regression.

Most importantly, I learned how ridge regularization can transform a horrible model that overfits a very small set of training data into a model that can make decent predictions. Ridge regression can even help make predictions when the number of features in your data exceeds the number of training examples, which was my case exactly!

This project is a learning lesson for me about the importance of good data and its size. I was ready to give this project up after I got bad results and thought it was pointless; however, learning about new concepts such as log transforms and ridge regularization showed me that there are simple but powerful techniques in ML making what seems impossible from one point-of-view possible from another.
