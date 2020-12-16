# Advertisement-Success-Prediction
This is a binary classification problem where you need to predict whether an ad buy will lead to a netgain.

Data Description
train.csv
It contains the training data with advertisement details as described in the last section

Data Dictionary
Variable	Description
UserID	Unique id for each row
ratings	Metric out of 1 which represents how much of the targeted demographic watched the advertisement
airlocation	Country of origin
airtime	Time when the advertisement was aired
average_runtime(minutes_per_week)	Minutes per week the advertisement was aired
targeted_sex	Sex that was mainly targeted for the advertisement
genre	The type of advertisement
industry	The industry to which the product belonged
relationship_status	The relationship status of the most responsive customers to the advertisement
expensive	A general measure of how expensive the product or service is that the ad is discussing
money_back_guarantee	Whether or not the product offers a refund in the case of customer dissatisfaction
netgain	Target, Whether the ad will incur a gain or loss when sold
test.csv
It has advertisement details for which the participants are to submit whether netgain would be there

sample_submission.csv
It contains the submission format for the predictions against the test set. A single CSV needs to be submitted as a solution.

Evaluation Metric

Submissions are evaluated using F1_Score(Binary)

