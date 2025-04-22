# 05_Predict_Product_Return_202401100300045
Classify whether an item will be returned based on purchase context and review.
🛍️ 05_Predict_Product_Return_202401100300045

This machine learning project predicts whether a product will be returned based on purchase context and customer reviews. It uses classification techniques and evaluates performance using metrics like accuracy, precision, and recall.
📁 Dataset

The dataset contains features such as:

    purchase_amount – total price of the purchase

    review_score – rating given by the customer

    days_to_delivery – number of days taken to deliver the product

    returned – target variable (1 = returned, 0 = not returned)

🧠 ML Approach

    Model Used: Random Forest Classifier

    Problem Type: Binary Classification

    Evaluation Metrics:

        Accuracy

        Precision

        Recall

        Confusion Matrix (Heatmap)

📊 Libraries Used

    pandas

    scikit-learn

    matplotlib

    seaborn

🚀 Steps Performed

    Loaded and cleaned the dataset

    Encoded categorical variables

    Split data into training and testing sets

    Trained a Random Forest Classifier

    Evaluated the model

    Plotted confusion matrix heatmap

📌 Output Example

    Accuracy: 0.87

    Precision: 0.85

    Recall: 0.80

    Confusion Matrix: Displayed as a heatmap using Seaborn

📂 Files Included

    product_return.csv — the dataset

    product_return_prediction.ipynb — the notebook/code

    README.md — project description

🧑‍💻 Author

    Name: Anirudh kumar

    Branch: B.Tech CSE (AI), KIET

    Year: 1st Year
