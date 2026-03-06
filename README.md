# House Price Prediction & Deployment
## Overview
[ Brief description of the project ]
## Dataset
- Source : USA Housing dataset
- Features used : [ list the features you selected ]
- Target : House Price
- Total samples : [ number ]
## Model Comparison
| Model | Train R | Test R | Test MSE |
|-------|----------|---------|----------|
| Linear Regression | 0.916 | 0.912 | 10 ,500 ,000 |
| Polynomial ( degree 2) + Ridge | 0.928 | 0.918 | 9 ,800 ,000 |
| KNN (k =5) | 0.945 | 0.901 | 11 ,200 ,000 |
## Final Model
** Model :** Polynomial Regression ( degree 2) + Ridge
** Test R :** 0.918
** Test MSE :** $9 ,800 ,000
** Why this model ?**
[ Explain why you chose this model based on performance
and EDA findings ]
## Web Application
Deployed using Gradio .
### Screenshots
![ Gradio Interface ]( screenshots / gradio_interface .png)
## Installation
git clone [your -repo -url]
cd house -price - prediction
pip install -r requirements .txt
## Usage
Run the web app:
python app.py
## Project Structure
house -price - prediction /
data /
notebooks /
1 _eda . ipynb
2 _training . ipynb
app .py
models /
README .md
## Technologies Used
- Python
- Pandas , NumPy , Matplotlib , Seaborn
- Scikit - learn
- Gradio
