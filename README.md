NLP Deep learning model with interactive visualization 

Deploying deep learning models directly through Heroku can be slow depending on the size of the model.
This is a demonstration of the practical usage of Streamlit to visualize the the results of a large deep learning model in Heroku instead.

Steps:
1. Run the deep learning model locally and save results.
   Model location: blstm_model/blstm_.py
2. Deploy a Streamlit application to visualize model results on Heroku. 

The Streamlit application for this model can be viewed here: https://bilstm.herokuapp.com/

Data: online job postings broken into skill categories as designated by ONET online. Preprocessing: 1. emails removed using regex 2. punctuation removed 3. lowercase transformation 4. stemmed

If you want to run the deep learning model in heroku directly, it can be viewed here: https://nlp-deep-learning.herokuapp.com/



