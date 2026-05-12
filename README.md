# concert-price-prediction

My first end-to-end machine learning project: predicting concert ticket prices from features like artist, genre, performance details, and date using linear, polynomial, and ridge regression. Dataset from AinaFih/Concerts_Dataset-Project - simulated concert data.

What I worked on:
- Data preprocessing in pandas: log transforms to reduce skew and linearise multiplicative relationships, one-hot encoding for categorical features, and cyclical (sin/cos) encoding for dates so the model treats December and January as adjacent.
- Exploratory analysis and outlier identification with matplotlib.
- Implemented k-fold cross-validation manually from the theoretical definition, then used it to compare models and tune the ridge regression alpha.
- Trained and compared plain linear, polynomial, and ridge-regularised versions of both.

What I learned:

The dataset had more features than training examples, so unregularised polynomial regression overfit catastrophically. Ridge regularisation turned what looked like an unusable model into one making reasonable predictions, a striking demonstration that the right technique can make a problem possible to solve even when the data seems against you.

Learning about log transforms and ridge regularisation showed me that simple techniques can make a big difference, and that an approach not working often just means there's a better one I haven't tried yet.
