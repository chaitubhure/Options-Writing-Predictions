# Options Writing Predictions

Stock market being the most tricky business, the main issue goes around for the writer “How to Make PROFIT”. From the studies we can see that more than the buyer it is the writers who get more loss. For balancing out one loss, he have to make many profits which is not technically possible for all the writers. To resolve this issue, we are coming up with solution of predicting the options for the writer and also when the expiry date has to fall on.

### Technology and platfroms

This project makes use of the [Google Colaboratory](https://colab.research.google.com/notebooks/welcome.ipynb#recent=true) platform. It took 10 minutes with a CPU to train the complete model on Colab and the other technologies used in this project are as follows:

* [Tensorflow-2.0](https://www.tensorflow.org/) - Most popular, deep learning framework
* [Pandas](https://pandas.pydata.org/) - Python library for performing operations on data

### Running the code

After installing the above mentioned dependencies, run the following commands in the Google Colab environment.

```
OUR ASSUMPTIONS:  OUT OF MONEY FOR COVERED CALL AND FOLLOWED BY A PUT:

Please follow our presentation file for our CALL and PUT considerations.

The implementation of the network and our reasoning behind how we suggested options is explained in our slides.

The code outputs a list of Option Suggestions based on model predictions for risk factors varying from 10-50%

Steps to implement:

1. The code impemented in Google Colab notebook is present in the folder "Chaitanya_Dylan_Jayashri" by the name "FinalStockPredictor.ipynb"

2. The training datasets by the name of F.csv and CVX.csv are present in the "Training Data" folder under "Chaitanya_Dylan_Jayashri"

3. Right click on the "FinalStockPredictor.ipynb" file, go to open with and select "Colaboratory".

4. The python notebook will open inside the Google colab platform.

5. A couple of steps to perform before you actually run the code.

   5.a. Make a foler by the name "BigData" inside your Google Drive and copy the training data files "F.csv" and "CVX.csv" to
		this folder.
   5.b. Now run, the first cell of the notebook. You should see a "play or run" icon on the left of the cell. Click on that.
		If you should receive a warning stating that this notebook was not authored by Google, just click on "Run anyway".
   5.c. Once, the cell starts executing, you will receive a link in the outputs section (just below the cell you are running),
		to get your "authorization code"
   5.d. Clicking on that link, will open a new tab in google chrome and you shall see your authorization code. Copy and paste
		that code into the rectangular box, in the outputs section of the cell you just ran and press enter. You should see the
		output change to "Mounted at content/drive"

6. The above step sets the environment with the correct paths and data files for the code to run.

7. Now, go to the second cell in the notebook. Go to Runtime, and click Run After or alternatively, you can go with "Ctrl+F10"
   This essentially runs, the current and all the other following cells, to give you the output. You should be able to the see
   the output of each cell, just below it.   

8. The code should execute within 15-30 mins and you will see the original stock data, the prediction for the last few days and a
   list of option suggestions with estimated gain and risk factor.
```

### High Level View of the Model and Working

![Overview of the model](https://github.com/chaitubhure/Options-Writing-Predictions/blob/master/Overviewofmodel.png)

### Authors

* [Chaitanya Bhure](https://github.com/chaitubhure)

### License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/chaitubhure/Options-Writing-Predictions/blob/master/LICENSE) file for details
