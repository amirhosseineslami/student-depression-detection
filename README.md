# 📊 Student Depression Detection Using Decision Tree

This project aims to detect student depression by training a **Decision Tree model** using Python and NumPy, leveraging a well-prepared dataset from Kaggle. It includes detailed preprocessing, feature analysis, model training, hyperparameter tuning, and evaluation to ensure optimal model performance while avoiding overfitting.

## 📁 Project Structure

* **Dataset Selection and Preprocessing**
  Selected a suitable dataset (`Student Depression Dataset`) from Kaggle. Applied cleaning steps such as:

  * Removing outliers
  * Mapping categorical to numeric values
  * Discretizing continuous features (e.g., age, CGPA)
  * Grouping low-frequency categories to reduce noise

* **Feature Engineering**
  Analysed features like:

  * Age, city, academic pressure, sleep duration, eating habits
  * Depression history, economic stress, CGPA, and more

* **Model Training**
  Implemented a Decision Tree classifier with:

  * Depth and min-sample-split tuning
  * Varying training/test split ratios
  * Iterative improvements to minimize overfitting

* **Evaluation**
  Focused on balancing:

  * Training accuracy vs. test accuracy
  * Precision in classification
  * Avoiding overfitting via pruning strategies

## 📈 Results

After parameter optimization and dataset refinements, the model achieved:

* **Training Accuracy**: \~85%
* **Testing Accuracy**: Comparable, with minimal overfitting

## 🛠 Technologies Used

* Python
* NumPy
* pandas
* scikit-learn (for decision tree)
* Google Colab (for execution environment)

## 📂 Dataset

* **Source**: [Kaggle - Student Depression Dataset](https://www.kaggle.com/)
* **Size**: \~27,900 samples, 18 features

## 🔍 Key Takeaways

* Proper preprocessing dramatically improves model accuracy
* Feature grouping and encoding can reduce model complexity
* Decision Trees are sensitive to overfitting — tuning is crucial

## 📚 References

* Course materials from Prof. Dr. Abdi
* [GeeksforGeeks](https://www.geeksforgeeks.org)
* ChatGPT 4o for analysis support
