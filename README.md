## Sentiment Analysis Of Reviews in Amazon Fine Food Review Dataset

<p> The dataset for the given notebook can be downloaded from <a href="https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews">Kaggle</a>.<p>

### Context
 <p> This dataset consists of reviews of fine foods from amazon. The data span a period of more than 10 years, including all ~500,000 reviews up to October 2012. Reviews include product and user information, ratings, and a plain text review. It also includes reviews from all other Amazon categories.</p>

The data includes:
* Reviews from Oct 1999 - Oct 2012
* 568,454 reviews
* 256,059 users
* 74,258 products
* 260 users with > 50 reviews

### Approach 
<p>Here, we perform sentiment analysis on a dataset of product reviews using the CLIP (Contrastive Language-Image Pre-Training) model. The code uses the pre-trained CLIP model provided by OpenAI and fine-tunes it on a dataset of product reviews. For more detailed explaination check out my article, <strong>Unleashing the Potential of Zero-Shot Classification with Contrastive Learning Using CLIP</strong> on <a href="https://medium.com/@shashankv.vats/unleashing-the-potential-of-zero-shot-classification-with-contrastive-learning-1d2567ea1b13">Medium</a>.
