Project Design and Coding


Flowchart Design:
![image](https://user-images.githubusercontent.com/120276263/211789326-a99be969-2419-4807-9a44-d0f21af87265.png)


Description of the project coding and implementation

Libraries and Packages required:
![image](https://user-images.githubusercontent.com/120276263/211789377-7200cc81-6096-4374-9c52-faddc08e81c0.png)


Heart disease prediction:
At first, we load our data from the Cleveland Dataset and filter it to remove null data, unnecessary information, and removing missing data. Below shows the code to implement it.
![image](https://user-images.githubusercontent.com/120276263/211789428-278c77bd-1dcc-4474-b610-2c4232cc6f69.png)


Next , we change the data to numerical because some of the attributes are object datatypes. Then we use it to plot histograms to each variables. 
![image](https://user-images.githubusercontent.com/120276263/211789475-25a4f8fa-51e4-4cd5-a8dd-aedd3bbcaaad.png)


Then we create train and test data by 70:30 to train the dataset and change the class column to binary as 0 = no heart disease and 1 = heart disease.
![image](https://user-images.githubusercontent.com/120276263/211789512-81e18efc-32a6-44a6-b4af-ff8cf7202b33.png)


At last we implemented the CNN technique using binary classification. We activated the sigmoid function in the model created. Then we compile it with the learning rate of 0.001. To know the model accuracy we have created accuracy plot and epoch plot. To know the model loss we have crated the  Then we print out who ever has threshold more than 0.5 as has heart disease and below 0.5 as no heart disease. 
 ![image](https://user-images.githubusercontent.com/120276263/211789563-b2a13d33-bdde-44a6-9ff0-41123ff07f98.png)
![image](https://user-images.githubusercontent.com/120276263/211789589-c2f162d4-7701-45a0-951c-1c6a4f214bcf.png)






Project Result
 ![image](https://user-images.githubusercontent.com/120276263/211789658-10eacd7d-3079-4fce-9f4b-5f4c7e70840a.png)
![image](https://user-images.githubusercontent.com/120276263/211789693-1083b666-2bdf-4e0a-ac62-fe6c36e902a0.png)
![image](https://user-images.githubusercontent.com/120276263/211789720-3080ae5f-5899-49f7-9af5-036dc26ac66e.png)

