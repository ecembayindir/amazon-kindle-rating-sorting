<h1 align="center">Rating Products & Sorting Reviews - Amazon Kindle</h1>

<br/>

<h2>🚀 <strong>Project Overview</strong></h2>
<p>
This project delves into analyzing reviews from Amazon's Kindle Store to address critical challenges in e-commerce:
</p>
<ul>
  <li><strong>Product Rating Accuracy:</strong> Enhancing product rating calculations to ensure fair and reliable representation.</li>
  <li><strong>Review Sorting:</strong> Ranking reviews to surface the most helpful and relevant ones, improving the overall user experience.</li>
</ul>
<p>
The dataset provides insights into user interactions and feedback on various books, allowing us to refine the evaluation of product ratings and optimize the visibility of reviews for informed decision-making.
</p>
<p><em>Dataset available on <a href="https://www.kaggle.com/datasets/bharadwaj6/kindle-reviews" target="_blank">Kaggle</a>.</em></p>


<h2>📈 <strong>Project Workflow</strong></h2>
<ul>
  <li><strong>Data Cleaning and Preparation:</strong> Processed the dataset to remove redundancies, convert date formats, and generate derived features such as `day_diff` (days since the review).</li>
  <li><strong>Product Rating Calculation:</strong> Compared simple averages with time-based and user-based weighted averages to provide nuanced insights.</li>
  <li><strong>Review Sorting:</strong> Implemented advanced metrics like Wilson Lower Bound to rank reviews by helpfulness and reliability.</li>
</ul>

<h2>🔍 <strong>Methods Applied</strong></h2>
<ul>
  <li><strong>Simple Average Rating:</strong> Calculated the mean rating across all reviews for a product.</li>
  <li><strong>Time-Based Weighted Rating:</strong> Penalized older reviews while giving more weight to recent ones to reflect current trends.</li>
  <li><strong>User-Based Weighted Rating:</strong> Adjusted ratings based on user engagement, prioritizing experienced reviewers.</li>
  <li><strong>Review Sorting Metrics:</strong> Used:
    <ul>
      <li>Positive-Negative Difference</li>
      <li>Average Rating</li>
      <li>Wilson Lower Bound (WLB)</li>
    </ul>
    to rank reviews by reliability and relevance.
  </li>
</ul>

<h2>🔧 <strong>Tools & Technologies Used</strong></h2>
<div align="center">
    <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" alt="Python"/>
    <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>
    <img src="https://img.shields.io/badge/numpy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/>
    <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white" alt="Matplotlib"/>
    <img src="https://img.shields.io/badge/scipy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white" alt="SciPy"/>
</div>

<h2>📊 <strong>Key Insights</strong></h2>
<ul>
  <li><strong>Enhanced Ratings:</strong> Time-based and user-based weights improve the accuracy of product ratings by incorporating temporal trends and user expertise.</li>
  <li><strong>Reliable Review Sorting:</strong> Wilson Lower Bound ensures unbiased ranking of reviews, surfacing the most helpful and trustworthy ones.</li>
  <li><strong>Actionable Recommendations:</strong> Insights support sellers in identifying trends and customers in making informed decisions.</li>
</ul>

<h2>📢 <strong>Contact</strong></h2>
<ul>
    <li><a href="https://www.linkedin.com/in/yourusername/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white" alt="LinkedIn"/></a></li>
    <li><a href="mailto:your.email@example.com"><img src="https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white" alt="Email"/></a></li>
</ul>

<p align="center">&copy; 2025 Your Name. All rights reserved.</p>

<hr>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=ecembayindir&repo=amazon-kindle-rating-sorting&label=Repository%20views&color=0e75b6&style=flat" alt="Repository Views">
</p>
