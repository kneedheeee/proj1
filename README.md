# GitHub User Data Analysis

- Analyzed GitHub users in Mumbai with over 50 followers, focusing on user profiles, activity, and repository data.
- Discovered correlations between profile attributes and follower counts, highlighting factors that may increase a user's visibility.
- Developed practical recommendations for developers to optimize their GitHub profiles for audience growth.

## Data Scraping Methodology

Using GitHub’s API, we gathered data on users based in Mumbai with follower counts exceeding 50. The script retrieves an initial list of users and iterates over each to fetch detailed information, including their company, public repositories, and preferred languages. Repository details such as stars and whether projects or wikis are enabled were also collected. The data is stored in CSV files for thorough analysis, with pagination and error handling to manage API rate limits and network issues effectively.

## Interesting Findings

1. **Bio Length and Followers**: There’s a positive relationship between bio length and follower count, with each additional word associated with a 0.458 increase in followers. This suggests that a well-crafted bio can contribute to follower growth.
   
2. **Repositories and Followers**: We found a modest correlation between the number of public repositories and followers, with each additional repository associated with about 0.1 more followers. However, focusing solely on repository quantity may not significantly boost follower count.

3. **Collaboration Features**: Users who enable both "projects" and "wiki" on their repositories often have higher follower counts, indicating a preference for collaborative features within the community.

## Actionable Recommendations

- **Optimize Bio**: Developers should craft a clear and engaging bio that highlights expertise, projects, and interests to attract more followers.
- **Focus on Quality over Quantity**: While having more repositories can correlate with a slight increase in followers, prioritizing high-quality and relevant projects might be more effective.
- **Enable Collaborative Features**: Enabling GitHub's project and wiki features can signal openness to collaboration, potentially enhancing user engagement and visibility.
