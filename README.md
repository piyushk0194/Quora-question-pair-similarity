# Quora-question-pair-similarity

Statement:
Quora is a question-and-answer site where questions are asked, answered, edited and organized by its community of users. Over 100 million people visit Quora every month, so it’s no surprise that many people ask similarly worded questions. Multiple questions with the same intent can cause seekers to spend more time finding the best answer to their question, and make writers feel they need to answer multiple versions of the same question.

Quora has publicly released the data set to mitigate the inefficiencies of having duplicate question pages at scale. Which gives us our problem statement : An automated way of detecting if pairs of question text actually correspond to semantically equivalent queries.

Data type: CSV files

Train data: train.csv (id, qid1, qid2, question1, question2, is_duplicate)

Test data : test.csv (id, qid1, qid2, question1, question2)

Total number of records in train data: 404351

Data Size: 130MB
