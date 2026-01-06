# AI-BASED-RECOMMENDATION-SYSTEM

*COMPANY*: CODETECH IT SOLUTIONS

*NAME*: GAJJELLY VARSHITHA

*INTERN ID*: CTIS0641

*DOMAIN*: JAVA PROGRAMMING

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

##DESCRIPTION

I complied this task in Eclipse platform.An AI-based recommendation system is an intelligent application designed to suggest products, services, or content to users based on their preferences, behavior, and interactions. In this project, a recommendation system is developed using Java and the Apache Mahout library to demonstrate how machine learning concepts can be applied to real-world personalization problems. Recommendation systems are widely used in modern applications such as e-commerce platforms, streaming services, social media, and online learning portals.

The core technique used in this project is collaborative filtering, specifically user-based collaborative filtering. Collaborative filtering works on the idea that users who have shown similar interests in the past are likely to have similar preferences in the future. Instead of analyzing the features of products, the system focuses on user behavior, such as ratings given to items. This makes the approach flexible and effective even when detailed product metadata is unavailable.

The system uses a sample dataset stored in a CSV file, where each row contains a user ID, an item ID, and a rating. Apache Mahout’s FileDataModel is used to load and process this data. Mahout automatically interprets the numerical values and constructs an internal model that represents the relationships between users and items. To measure similarity between users, the Pearson Correlation Similarity method is applied. This statistical technique compares rating patterns and determines how closely related two users are based on their preferences.

Once similarity is calculated, the system identifies a neighborhood of users with similar tastes using the Nearest N User Neighborhood approach. Based on this neighborhood, the recommender engine predicts which items a target user may like but has not yet rated. The GenericUserBasedRecommender class is then used to generate a list of recommended items along with confidence scores that indicate the strength of each recommendation.

The Java program is executed in an IDE such as Eclipse, where the dataset is read, processed, and analyzed at runtime. The final output displays recommended item IDs for a selected user, demonstrating that the system successfully suggests new content based on learned patterns. Although the dataset used is small, the same approach can be scaled to large datasets in real-world applications.

This project highlights the practical implementation of artificial intelligence concepts such as data modeling, similarity measurement, and predictive analysis. It provides hands-on experience with Apache Mahout and illustrates how recommendation engines enhance user experience by delivering personalized suggestions. Overall, the AI-based recommendation system demonstrates how machine learning can be effectively integrated with Java to solve meaningful and industry-relevant problems.

##OUTPUT

<img width="971" height="272" alt="Image" src="https://github.com/user-attachments/assets/d9b9cbc8-7373-4859-8b13-a314e16964b0" />
