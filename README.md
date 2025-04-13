Task – 1 (Dataset Selection and Model Training):
The dataset, I chose, was a simple dataset of Temperature vs Ice Cream units sold. The dataset was picked up from Kaggle with the below link.
Dataset: https://www.kaggle.com/datasets/mirajdeepbhandari/polynomial-regression
It only had one feature of Temperature (‘C), and the dataset trend resembled a polynomial regression one. Three other models were trained using gradient descent using sklearn module. But the main model chosen was the polynomial regression model, because it gave the least error. The model training was pushing onto github, with the below link.

Github repo link: https://github.com/Wania-n/ML_A-03_IceCream

Task – 2 (Hugging Face):
I saved the polynomial regression model as poly_model.pkl. uploaded that on hugging face. The hugging face repo is as follows:

Hugging Face repo: https://huggingface.co/Wania-n/poly-regression-model/tree/main

The poly_transform.pkl is also added, because that is needed to transform the features for the polynomial regression.

Task – 3 (Inference File):
I created an inference file named interfence.py, where I have written functions for predicting, loading the model etc. This file is also uploaded on hugging face.

Task – 4 (W&B):
I created an account at wandb, and connected it to my hugging face repo folder, so that all the logs of weights and biases are recording everytime the model is run. Below is the link to the workspace for this model.

Wandb account link: https://wandb.ai/wanianaeem48-national-university-of-computer-and-emergin/icecream-temp-regression?nw=nwuserwanianaeem48

Task – 5 (Web UI and Running the Model):
I set up the app.py and index.html in the hugging face repo folder and created a very simple UI for the inference reports. Since I didn’t deploy it, simply, download the hugging face repo raw. And run python app.py on the command terminal of that folder. The project is run locally.

