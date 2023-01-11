Project Design and Coding
Flowchart Design:


Description of the project coding and implementation
Libraries and Packages required:

Heart disease prediction:
At first, we load our data from the Cleveland Dataset and filter it to remove null data, unnecessary information, and removing missing data. Below shows the code to implement it.

Next , we change the data to numerical because some of the attributes are object datatypes. Then we use it to plot histograms to each variables. 

Then we create train and test data by 70:30 to train the dataset and change the class column to binary as 0 = no heart disease and 1 = heart disease.

At last we implemented the CNN technique using binary classification. We activated the sigmoid function in the model created. Then we compile it with the learning rate of 0.001. To know the model accuracy we have created accuracy plot and epoch plot. To know the model loss we have crated the  Then we print out who ever has threshold more than 0.5 as has heart disease and below 0.5 as no heart disease. 






Project Result




