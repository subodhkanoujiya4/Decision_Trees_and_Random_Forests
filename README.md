# ❤️ Heart Disease Prediction using Decision Trees & Random Forests
This project demonstrates the use of Decision Tree and Random Forest classifiers to predict the presence of heart disease using the heart.csv dataset. It includes tree visualization, feature importance analysis, and cross-validation to evaluate model performance.

# 📁 Dataset
File: heart.csv

Rows: 1025
Target column: target (1 = Heart Disease, 0 = No Disease)
Features: 13 numeric/categorical-encoded features such as age, cp, chol, thal, etc.

# 🧰 Tools Used
Python 🐍
Pandas, NumPy
Scikit-learn
Seaborn, Matplotlib
Graphviz (optional for .dot tree exports)

# 🧠 Tasks Performed
✅ 1. Train a Decision Tree Classifier
Trained on 80% of the data
Visualized top 3 levels of the tree
Analyzed performance using classification report and accuracy
✅ 2. Control Overfitting
Limited tree depth using max_depth=4
Compared pruned tree accuracy and overfitting behavior
✅ 3. Train a Random Forest Classifier
Used 100 trees (n_estimators=100)
Compared with Decision Tree results
✅ 4. Feature Importance Interpretation
Visualized top 10 most important features influencing the prediction

✅ 5. Model Evaluation using Cross-Validation
5-fold cross-validation on both models
Reported average accuracy

# 📈 Results
Model	Accuracy (Test)	Cross-Validation Accuracy
Decision Tree	98.5%	–
Pruned Tree (depth=4)	80.0%	83.4%
Random Forest	98.5%	99.7%
✅ Random Forest performed the best with highest accuracy and generalization.

# 📊 Visualizations Included
Decision Tree structure (first 3 levels)
Top 10 feature importances (bar plot)
# 🚀 How to Run
# Clone the repository
git clone https://github.com/your-username/heart-disease-trees.git
cd heart-disease-trees

# Install dependencies
pip install pandas numpy scikit-learn matplotlib seaborn

# Run the Python script or notebook
python heart_tree_models.py
# OR open heart_tree_models.ipynb
Ensure heart.csv is in the same folder as your script or notebook.

# 📂 Project Structure

# 📦 heart-disease-trees/
 ┣ 📄 heart.csv
 ┣ 📄 heart_tree_models.py
 ┣ 📄 heart_tree_models.ipynb
 ┗ 📄 README.md
# 👨‍💻 Author
Subodh Kanoujiya
Connect on LinkedIn | GitHub: @subodhkanoujiya4
