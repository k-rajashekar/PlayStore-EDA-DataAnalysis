📱 Google Play Store App & User Review Analysis
This repository contains an end-to-end exploratory data analysis (EDA) project focused on Google Play Store apps and user reviews. The goal is to identify key drivers of app engagement, user satisfaction, and market performance through insightful visualizations and statistical observations.

📌 Project Objective
To analyze app-level metadata and user sentiment data from the Google Play Store to discover:

What types of apps dominate the market?

How do pricing, size, and category affect ratings?

How do user sentiments relate to app success?

What factors most influence app installs, ratings, and reviews?

🧠 Thought Process
This project began with a real-world question: Why do some apps succeed while others fail?
With over 3 million apps available, we wanted to explore what patterns exist in high-performing apps. We approached this by combining app metadata with real user review sentiments to see how technical attributes align with public perception.

📂 Dataset Description
The project uses two datasets:

googleplaystore.csv: Contains metadata like app name, category, rating, reviews, size, installs, type, price, and more.

googleplaystore_user_reviews.csv: Includes textual user reviews along with precomputed sentiment polarity and subjectivity.

Together, these datasets provide both quantitative and qualitative insights into app success factors.

🔧 Technologies Used
Tool / Library	Purpose
Python	Core programming language
Pandas & NumPy	Data wrangling and manipulation
Matplotlib & Seaborn	Visualizations and charting
Google Colab	Interactive development environment

🚀 How to Run the Project
You can easily run this project using Google Colab, which requires no local setup.

✅ Steps to Run on Google Colab:
Open the Notebook on Colab

Click here to open in Colab

Or go to https://colab.research.google.com

Upload the Notebook

Click on "File" → "Upload Notebook"

Select the file PlayStore_EDA_Git_Version.ipynb from your system

Upload the Datasets

Once the notebook opens, upload the dataset files when prompted using the Upload buttons (or run the upload cell):

googleplaystore.csv

googleplaystore_user_reviews.csv

Run All Cells

Click on "Runtime" → "Run all"

Make sure all visualizations load successfully, and no errors appear.

Explore & Modify

You can tweak the code or visualizations directly within the Colab interface.

💡 Google Colab is free and cloud-hosted — no installation or setup required.
