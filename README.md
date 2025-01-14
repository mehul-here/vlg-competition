# VLG Competition Repository

This repository documents my progress and solution to the unique challenge presented by the Vision and Language Group (VLG). The competition required classifying 50 animal classes, but the training set provided data for only 40 classes, creating a significant challenge.

---

## Repository Structure

### 1. **Daily Progress**
- Each day directory containing updates for each day of progress.
- Each day's folder includes:
  - The problem encountered on that day.
  - My thought process and the solution implemented.
  - An updated notebook and CSV file, with the exception of **Day 5**.

### 2. **Final Notebook and Thoughts**
- A directory containing:
  - The **final notebook** with detailed comments and refinements.
  - A write-up of my final thoughts and reflections on the competition.

### 3. **Report File**
- A detailed report on the model, explaining its architecture and performance in depth.

### 4. **Other Data Used**
- A directory with links to external datasets utilized for classes not included in the training dataset.
- This ensures that the model can be fully replicated.

---

## Brief Summary of the Model

### 1. **Handling Missing Classes**
- The model incorporates external data for the 10 left-out classes, enhancing its ability to generalize across all 50 classes.

### 2. **Preprocessing**
- Utilizes **DenseNet's built-in preprocessing** to scale input arrays effectively.

### 3. **Model Architecture**
- The initial layers leverage the **DenseNet convolution layer** for feature extraction from images.
- These are followed by a **dense network** to process the extracted features.

### 4. **Compilation**
- The model is compiled with:
  - **Adam optimizer**
  - **Accuracy as the evaluation metric**

### 5. **Overfitting and Underfitting Prevention**
- Overfitting reduction measures:
  - Inclusion of **dropout layers**.
  - Application of **L2 regularization**.
- Underfitting prevention:
  - Using **accuracy as a metric**.
  - Setting a **low learning rate** of `1e-4`.

---

This repository reflects my thought process, daily challenges, and the steps taken to overcome them, culminating in a robust model for the competition.