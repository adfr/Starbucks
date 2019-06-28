# Starbucks Recommendation engine



### Objective
Provide a classification of the offer Starbucks sends 


### Folders
<pre>
Figure8/
├── README.md  
├── Starbucks_Capstone_notebook  
├── data/  
	├── portfolio.json
	├──	profile.json  
	└── transcrip.json     

</pre>

### Instructions:
1. Run the notebook, the model is save in a pickle file.

2. To use the model you need to use a predict function of the randomForestClassifier. 

For instance, data will be:
pd.DataFrame( data = { 'difficulty' : [5], 'duration' :[5],'reward_y':[10],
                        'bogo':[1], 'discount':[0],'email':[0], 'informational':[0],
                      'age':[25],'income':[60000],
                      'F':[0], 'M':[1], 
                      'membership':[1000]})

### Results

Almost 70% accuracy on the offer BOGO or discount.


