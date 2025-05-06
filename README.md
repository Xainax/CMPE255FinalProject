# CMPE255FinalProject

# Instructions to run the Jupyter notebook
1. Clone the GitHub repo or make sure you have these files downloaded: PhiUSIIL_Phishing_URL_Dataset.csv, Updated_model(1).ipynb, and url_classifier_model.joblib.
2. After having the files downloaded, you can run and open the Jupyter notebook.
3. In the Jupyter notebook, run the first cell block to ensure you have all the necessary libraries installed. You can also run the following command to download all the necessary libraries:
`pip install pandas numpy joblib matplotlib seaborn scikit-learn xgboost tldextract beautifulsoup4 requests`
4. Once you have all the libraries installed, you can run everything on the Jupyter notebook, but every code block has an output.
5. To run the URL prediction, make sure you run the cell block with the function train_model_and_save to export the joblib model. Afterwards, you can run the function test_random_url and change the URL to test the model.
