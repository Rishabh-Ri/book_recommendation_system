# book_recommendation_system
Recommendation plays a huge role in boosting the customer/users experience. Book recommendation can help the book lovers to find a perfect book whom they should read next according to their interest or preference.
Now-a-days, online rating and reviews are playing an important role in books 
sales. Readers were buying books depend on the reviews and ratings by the others. 
Recommender system focuses on the reviews and ratings by the others and filters 
books. In this paper, Hybrid recommender system is used to boost our 
recommendations. The technique used by recommender systems is Collaborative 
filtering. This technique filters information by collecting data from other users. 
Collaborative filtering systems apply the similarity index-based technique. The ratings 
of those items by the users who have rated both items determine the similarity of the 
items. The similarity of users is determined by the similarity of the ratings given by 
the users to an item. Content-based filtering uses the description of the items and gives
recommendations which are similar to the description of the items. With these two 
filtering systems, books are recommended not only based on the user’s behaviour but 
also with the content of the books. So, our recommendation system recommends 
books to the new users also. In this recommender system, books are recommended 
based on collaborative filtering technique and similar books are shown using content 
based filtering.
The required dataset for the training and testing of our model is downloaded 
from Good-Reads website. Matrix Factorization technique such as Truncated-SVD 
which takes sparse matrix of dataset is used for reduction of features. The reduced 
dataset is used for clustering to build a recommendation system. Clustering is a 
collaborative filtering technique that is used to build our recommendation system in 
which data points are grouped into clusters. . In this paper, we used two methods i.e., 
K-means and Gaussian mixture for clustering the users. The better model is selected 
based on the silhouette score and used for clustering. Silhouette score or silhouette 
coefficient is used to calculate how good the clustering is done. Negative value shows 
that clustering is imperfect whereas positive value shows that clustering was done 
perfectly. Difference between the mean rating before clustering and after clustering is 
calculated. Root Mean square Error is used to measure the error between the absolute 
1
values and obtained values. That RMSE value is used to find the fundamental 
accuracy.
