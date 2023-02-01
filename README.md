# machine_hack
a repository for my files and models for the coupon code hackathon
What is the metric in this competition? How is the leaderboard calculated?
The submission will be evaluated using the Log Loss metric. One can use sklearn.metric.log_loss to calculate the same
This hackathon supports private and public leaderboards
The public leaderboard is evaluated on 30% of Test data
The private leaderboard will be made available at the end of the hackathon which will be evaluated on 100% of Test data
The Final Score represents the score achieved based on the Best Score on the public leaderboard
How to generate a valid submission File?
Sklearn models support the predict() method to generate the predicted values
The participant should submit a .csv file with exactly  15000 rows with 1 column ['calculated_total_amount']. The submission will return an Invalid Score if you have extra rows or columns.
The file should have exactly 1 column.
