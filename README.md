# Sentimental-analysis-and-EDA
Social Media Analytics Project
For this assignment, imagine yourself in the role of an analyst who was recently hired by a business intelligence firm (or by an internal analytics group of an investment group). You will perform an analytics task and provide a report outlining the approach you have taken.

For this specific task, you should choose only ONE of the following categories:

Facebook page activity tracking.
Once you have chosen a category, select a business intelligence objective within that category along the lines of what has been done in class. However, please make sure that your analysis differs from the specific task you have done as a part of the group (e.g. different company/brand, different area of trends mining etc.). We are letting you be creative with the task and pursue your interests relying on the skills you have learned in class.

Please perform your analysis using Python programming language, in line with the rest of the classwork.
# Application
• We used to download the Facebook comment dataset from the Kaggle website which is the best dataset provider.
• For the code we already used “fb_sentiment.txt” for analysis of kindle amazon Facebook comment, you can use your own Facebook comment using this code to analyze your own comments or create a file in text format and try it for simplification.
We follow these major steps in our program:
• Downloading(fetching) Facebook comment from Kaggle site and save it as text format.
• Preprocessing the data through SkLearn and nltk libraries. We first tokenize the data and then after tokenizing we stemize and lemmatize.
