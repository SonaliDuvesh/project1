# TDS Project 1

**Data Scraping Process:** We used the GitHub API to collect user data for developers in Seattle with over 200 followers, along with repository information, splitting the task into separate scripts to optimize efficiency and avoid rate limits.

**Interesting Finding:** Our analysis revealed that JavaScript is the most commonly used language, yet Haml repositories tend to have higher average star counts, highlighting its popularity and community engagement among followers.

**Recommendation for Developers:** Developers in Seattle aiming for visibility should consider contributing to Haml projects, as repositories in this language have a higher chance of engagement, which may help increase their follower count.

*Project overview:* This project uses GitHub's REST API to scrape user and repository data for developers based in Seattle with a follower count exceeding 200. The goal is to analyze trends in programming languages, engagement metrics, and company affiliation.

Data COllection Approach:

1. User Data Extraction: A script (fetch_users) was crested to gather user details and save them in users.csv. It uses pagination to capture multiple pages of users.

2. Repository Data Extractoin: The second script (fetch_repos) reads users.csv to fetch repositories for each user, saving the data in repositories.csv. This split approach avoids redundant requests and ensures efficiency.
   
**Key Analysis Findings:**

1. Top Languages: JavaScript and Haml are the most popular languages among Seattle developers in our dataset.

2. Engagement Pattern: Haml repositories, on average have a higher star count per repository, indicating greater community interest.
