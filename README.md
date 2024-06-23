# Movie Recommendations Analysis - Jupyter Lab
Analyzes movie data to recommend similar movies based on title selection and movie overview description.
<br> 
The resulting code could then be used in a visualization or web-app.
<br>

### Popularity-based recommendation
    - Uses quantile and mean methods, and a Weighted Rating formula
      used by IMDB for determining popularity.
        wr = ((v / v+m) * R) + (m / (v+m) * C)

### Content-based recommendation
    - Uses scikit-learn's TfidfVectorizer to implement Term Frequency 
      and Inverse Document Frequency, which determines similarities 
      from a single 'overview' data point. 