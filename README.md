# Machine-Learning-Practical-Assignment-1

## House Price Prediction


### create a virtual env

conda create --name Assignment-01-regression

### actaivate the virtual env

conda activate Assignment-01-regression

## Install the requrienments

pip install -r .\requirements.txt


## Build and save the model
python src/pipeline/training_pipeline.py


## RUN Flask app
python app.py

## Deploy the App
Go to render.com dashboard
create web service 
get SERVICE_ID and RENDER_TOKEN and update in GITHUB SECRETS