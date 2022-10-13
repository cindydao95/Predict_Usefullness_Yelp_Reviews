# Predict_Usefullness_Yelp_Reviews

Abstract
Online review strongly influences potential customers on the buying products or service decision. However, many online reviews are found as fake or not useful reviews for customers. It means the reviews does not reflect the real value of business. There are many research papers which have determined the features to predict whether the reviews are fake or not. Besides that, some papers have evaluated the helpfulness or usefulness of the reviews. They use different types of platforms such as, reviews from Yelp, TripAdvisor, Amazon, etc on different areas like, restaurant, hotels, or service. This research mainly focuses on evaluating the usefulness of reviews from restaurant in Texas. 



Part 1.	Collect/Download datasets from Yelp

		3 Files: “yelp_academic_dataset_business.json”, “yelp_academic_dataset_review.json”, and “yelp_academic_dataset_user.json”.

Part 2.	Convert three JSON format files to CSV format. 
		Input datasets: “yelp_academic_dataset_business.json”, “yelp_academic_dataset_review.json”, and “yelp_academic_dataset_user.json”.

		Jupyter Source File: part2_from_Bussiness_Data_JSON_to_CSV.jpynb, part2_From_Review_data_Json_to_CSV.jpynb, part2_from_user_data_Json_to_CSV.jpynb.

		Output datasets: "yelp_business.csv", "user_dataset_updated1.csv", and "review_dataset.csv"
Part 3.	Combine 3 CSV files

		Input datasets: "yelp_business.csv", "user_dataset_updated1.csv", and "review_dataset.csv"

		Jupyter Source File: combined_data.ipynb

		After converting three files above, I have 3 dataset files in CSV format named 
		Output dataset : restaurant_dataset_updated.csv


Part 4.	Preprocessing data/Feature Engineering and build logistic regression model and deep learning model to predict the usefulness of reviews

		Input dataset: restaurant_dataset_updated.csv
		
		Jupyter Source File: feature_engineering.jpynb


Note: Will get the datasets in the outputDataset folder if you run all the above codes
