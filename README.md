
# A content based movie recommender system using cosine similarity and tmdb-dataset
                                             
                                                
                                                
 # How to get the API key?
Create an account in https://www.themoviedb.org/, click on the API link from the left hand sidebar in my  account settings and fill all the details to apply for API key.

# How to run the project?
1. Clone or download this repository to your local machine.
2. Then create a Proc file which helps to run streamlit app at heroku server
3. After that I create a setup.sh (Batch file) and write os related commands  to make  directory
4.Create a new file requirements.txt file with the command pip  freeze > requirements.txt
5.Get  the  API key from https://www.themoviedb.org/. (Refer the above section on how to get the API key)
6. Replace  API_KEY  at line no. 8 and then save it
7.Then open the terminal and run the file app.py by executing the streamlit run app.py
And it privides
Local URL: http://localhost:8501  
Network URL: http://192.168.0.107:8501

# Similarity Score:
How does it decide which item is most similar to the item user likes? Here come the similarity scores.
It is a numerical value ranges between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. This similarity score is obtained measuring the similarity between the text details of both of the items. So, similarity score is the measure of similarity between given text details of two items. This can be done by cosine-similarity.


# How Cosine Similarity works?
Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.


![download](https://user-images.githubusercontent.com/122508373/230754885-b8705663-969e-47d6-8384-6fd977475ebb.png)

