# searchFinalProject

In the project we have built a recommendation system for users and also created a service for businesses to help them identify the driving factors for their businesses.<br><br>
We have used the data from yelp for this purpose . The link to the data is below : <br> <br>
                https://www.yelp.com/dataset/download
Please download the libraries using requirements.txt file
## File explanation
1. We use "generate_task1_data.py" to subsample pizza related businesses and get a smaller dataset.
2. We use "cleaning_attributes_of_businesses.ipynb" to clean the attributes of the businesses and create a json file that contains only the attributes in a valid json format. This file takes business.json as the input.
3. "Preprocessing_data.ipynb" cleans, normalizes and preprocesses our dataset and creates a new file that contains all the features for all reviews that we want to use (except review text).
4. "text_extraction.py" extracts the review text and gives us vectorized review text.
5. "Embedded_bias_model.py" implements Task1 model 1.
6. "Embedded_nn_model" files implement task1 model 2.
7. "Memory_embeddings" file creates the embeddings that are used in task 1 model 2.
8. "TASK_2_lime_plus_shaply.ipynb" implements task 2.
