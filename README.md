## Kindle Sentimental Analysis

### Introduction
This project focuses on performing sentiment analysis on book reviews from the Amazon Kindle Store category using the Bag of Words (BOW) model. The goal is to analyze the sentiments expressed in the reviews and derive meaningful insights from the data.

### Setup and Installation Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/sanskaryo/Kindle_Sentimental_analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Kindle_Sentimental_analysis
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Usage Guidelines
1. Load the dataset and preprocess the data.
2. Apply the Bag of Words model to convert text data into numerical features.
3. Perform sentiment analysis using appropriate machine learning models.
4. Evaluate the model performance and derive insights.

### About Dataset
#### Context
This is a small subset of the dataset of book reviews from the Amazon Kindle Store category.

#### Content
The dataset contains 982,619 entries of product reviews from the Amazon Kindle Store category from May 1996 to July 2014. Each reviewer has at least 5 reviews, and each product has at least 5 reviews in this dataset.

#### Columns
- **asin**: ID of the product, e.g., B000FA64PK
- **helpful**: Helpfulness rating of the review, e.g., 2/3
- **overall**: Rating of the product
- **reviewText**: Text of the review
- **reviewTime**: Time of the review (raw format)
- **reviewerID**: ID of the reviewer, e.g., A3SPTOKDG7WBLN
- **reviewerName**: Name of the reviewer
- **summary**: Summary of the review
- **unixReviewTime**: Unix timestamp of the review

#### Acknowledgements
This dataset is taken from Amazon product data, Julian McAuley, UCSD website. [Link to dataset](http://jmcauley.ucsd.edu/data/amazon/)

#### License
The license to the data files belongs to the original creators.

#### Inspiration
- Sentiment analysis on reviews.
- Understanding factors influencing the helpfulness of a review.
- Detecting fake reviews or outliers.
- Identifying best-rated product IDs or similarities between products based on reviews.

### Contributors
If you have any questions or suggestions, feel free to reach out to the project maintainers.

### License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

Feel free to customize the README.md file further based on your project's specific needs.
