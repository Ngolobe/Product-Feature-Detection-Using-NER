# Product-Feature-Detection-Using-NER
Simplifio is a company that creates data-driven solutions for a pool of their customers.

This project specifically consists of developing a NER model for one of their client. 

In the files attached, we share our approach to how we developed our own custom NER model using SpaCy.  The project includes:  data.csv; fixed_train_data.json/.txt; train_file_custom_NER; test_file_custom_NER; model folder.   

The data.csv file is the customer data we received. This file contains total 8 features/columns and over 600,000 samples/products based on the titles they are listed under on the website.  
fixed_train_data.json/txt is the training dataset in the format as required by ScaPy. It has around 1000 training examples.  
train_file_custom_NER contains the information about the training process of our custom model. We suggest not to run this file unless necessary.  
The test_file_custom_NER will take you through the testing procedure that we undertook.  
In the model folder, you can find the trained custom NER model with all the required files. This model can be used to test any similar unseen data.
