# NPClassifer_local
This app is a local version of NPClassifier: https://github.com/mwang87/NP-Classifier <br><br>
Instead of having neural networks trained then hosted on UCSD servers, the neural networks are trained and stored in the 'trained_models' folder. This version of the app also has a 'batch processing' section so you can upload excel files and do multiple classifications at a time without needing to script.

## Instructions
'''shell
# clone
git clone https://github.com/grantmcc98/NPClassifer_local.git

# cd to directory
cd NPClassifier_local

# unzip zipped folders

# install libraries
pip install -r requirements.txt

# Start app
python app.py
'''
The app will run locally at http://127.0.0.1:8080/
