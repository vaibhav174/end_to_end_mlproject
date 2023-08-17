## End to End Machine Learning Project

<b>NOTE: This is the replication of the health insurance premium price prediction project on a dummy dataset from kaggle. The actual project is under production for a NGO link to which will be shared once the project goes live.</b>

The notebook folder contain ipynb files for data analysis and model training. Please refer to this folder to see the whole idea in on place.

different components of the pipeline in present in the src folder

The best model is already trained and deployed using flask web app (app.py).

To use the trained model run the following command in terminal

python app.py

and go to address http://127.0.0.1:5000/predictdata insert the values of indicated fields and get prediction.

To retrain the model run 
python src/components/data_ingestion.py
