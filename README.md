1. Clean and prepare the data
- 	In this exercise, we consider only most frequent 3000 words of 		dictionary from email. 

	make_Dictionary reads the email files from a folder, constructs a dictionary for all words. Next, we delete words of length 1 and that are not purely alphabetical.

	At last we only extract out 3000 most common words.

2. Extracting features and label matrix
-	with the help of dictionary, we generate a label and word 			frequency matrix

3. Using sklearn Naive Bayes to train and predict
- 	Gaussian model is used for model training, it assumes that 				features follow a normal distribution. (Gaussian > Multinomial > 		Bernoulli for this data)

4. Accuracy Score
- 	Next we compare the accuracy score for predicted labels. sklearn 	provides implementation for acc score calculation.

96.54 % Accuracy Score! with 3000 most frequent words. (Using Gaussian Model)