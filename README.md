# Starbucks Recommendation engine

![Starbucks](logo_starbucks.png=250x250)

### Objective
Provide a classification of the offer Starbucks sends helping them to target in a better way the offer they send to loyalty program members.
In the notebook, we perform some data exploration, modelling, we fit a naive logistic model and then dive deeper into the features we use and fit a more robust and accurate random forest model.


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
1. Run the notebook, the model is saved in a pickle file.

2. To use the model you need to use a predict function of the randomForestClassifier. 

For instance, data will be in the following format to use the model:
pd.DataFrame( data = { 'difficulty' : [5], 'duration' :[5],'reward_y':[10],
                        'bogo':[1], 'discount':[0],'email':[0], 'informational':[0],
                      'age':[25],'income':[60000],
                      'F':[0], 'M':[1], 
                      'membership':[1000]})

### Results

Almost 70% accuracy on the offer BOGO or discount.
The model can be used to determined how effective the campaign will be for which individual.
I wrote a medium post liked to this github folder: https://medium.com/starbucks-who-to-give-discount-to/a-random-forest-approach-to-selecting-who-should-receive-which-offer-46adc09adb21


