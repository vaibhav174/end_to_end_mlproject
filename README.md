## End to End MAchine Learning Project

<b>NOTE: This is the replication of the health insurance premium price prediction project on a dummy dataset from kaggle. The actual project is under production for a NGO link to which will be shared once the projct goes live.</b>



The best model is already trained and deployed using flask web app.

To use the trained model run the following command in terminal

python app.py

and go to address http://127.0.0.1:5000/predictdata insert the values of indicated fields and get prediction.

To retrain the model run 
python src/components/data_ingestion.py
