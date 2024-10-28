
- I scraped GitHub users in Seattle with over 200 followers using the GitHub API.
- I discovered that most repositories are dominated by JavaScript, Python, and Ruby, but many repositories lack a specified language.
- Developers should consider adding language metadata and more detailed READMEs to improve visibility and collaboration.

## Project Overview
This project collects data on GitHub users based in Seattle with more than 200 followers and their public repositories. The data is stored in two CSV files: `users.csv` and `repositories.csv`.

### Data Files
- **users.csv**: Contains details about users including username, company, location, and follower count.
- **repositories.csv**: Contains details about each user's public repositories such as repository name, language, and stars.

### How to Use
To run this analysis or extend it, use the included Python scripts in this repository. You’ll need a GitHub API token to fetch the data.
