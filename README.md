# Customer_Review_Rating
Background
Customer reviews play a pivotal role in shaping business reputations and influencing consumer decisions. Analyzing these reviews to extract meaningful insights and ratings can be a time-consuming task, especially when dealing with large datasets. The NN-LLM project aims to address this challenge by leveraging the efficiency of the DistilBERT model to provide fast and accurate customer review rating predictions.

Why DistilBERT?
DistilBERT, a distilled version of the BERT model, offers similar performance to BERT but with significantly fewer parameters. This reduction in model complexity results in faster inference times while maintaining competitive predictive accuracy. By choosing DistilBERT, we strike a balance between speed and performance, making it an ideal candidate for real-time applications like customer review rating analysis.

Dataset
We have used the Yelp Review Dataset from Hugging Face for training and evaluating our fine-tuned DistilBERT model. This dataset contains a diverse collection of customer reviews, each associated with a star rating ranging from 1 to 5. The reviews encompass a wide array of businesses and domains, ensuring the model's versatility and applicability across various industries.
Link :- https://huggingface.co/datasets/yelp_review_full/viewer/yelp_review_full/train?row=21
