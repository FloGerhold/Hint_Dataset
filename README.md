# Hint_Dataset
This Github Repository contains a Question, Answer, Hints Dataset. 

It consists of the following features:

* Question: A Wikipedia-article-based question.
* Answer: The answer to the question
* Link: A link to the Wikipedia article
* Hint1: The first hint
* Hint2: The second hint
* ...
* Hint5: The fifth hint
* Rank1: The ranking of the first hint
* ...
* Rank5: The ranking of the fifth hint

The dataset was created with Amazon Mechanical Turk (MTurk).
Workers were asked to write five hints using the Wikipedia article as their knowledge-base.
Once they wrote all five hints, they were asked to rank their hints based on usefullness. The hint is ranked better if a user is more likely to get towards the correct answer. 1 is assigned to the best hint and 5 is assigned to the worst hint.


