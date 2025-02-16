# Guilty-or-Not-Guilty-Prediction-Competition
Raw Data Feature Extract &amp; Predict Traffic Violation Judgements Using RandomForestClassifier

# What's going on?
This is a competition on Kaggle. Creating a classifier, which given case details (like Plate Number, Violation, Penalty Amount etc.) of a traffic violation passes a judgment. Each data point has 17 features - which are a mix of strings, floats, integers, categorical variables etc. The training dataset contains cases of traffic violations over the years with labels being one of 15 possible judgments. Features (case details) and judgments are explained in attributes.xlsx.

# What I have done?
1. Raw data process & feature extraction (in "code" file, see trnNpred.py or other python files with prefix "trnNpred").
2. Model parameter tunning (in "code" file, see trnNpred.py or other python files with prefix "trnNpred").
3. Generate prediction (in "prediction submit" file).

# What's the result?
1. Rank #2, 77 teams in total.
2. Private Score(65% of the test data):0.85936.
3. Public Score(35% of the test data):0.85936.
