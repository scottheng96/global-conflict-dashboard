# global-conflict-dashboard

- web-based dashboard showing component-based information about global conflict news
- components:
  1. Conflict Newsfeed

### Conflict Newsfeed
- written in python
1. Download webpage and parse the html
2. Use BeautifulSoup package to parse html efficiently
3. Obtain for all articles
   - headline
   - date
   - image (generate unique_id)
   - text
   - topic (?)
4. add to data:
   - news_source (BBC, CNN, etc.)
   - created_at (when record was processed)
5. Save outputs into json file
   - link unique_id of images in json data
   - save images into separate folder (decide on standardized prefix)

Dockerize project
Run project as a docker image
See if can deploy on AWS and save outputs to s3 in AWS (check free tier providings)

Resources:
https://oxylabs.io/blog/news-scraping