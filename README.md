# Hacker News SQL Analysis
### "What Makes a Post Go Viral?"

## Overview
SQL analysis of millions of Hacker News posts using 
Google BigQuery to find what drives viral content.

## Tool Used
- SQL (BigQuery)
- Python (pandas)
- Kaggle Notebooks

## Dataset
bigquery-public-data.hacker_news.full

## Business Questions Answered
1. What are the top 10 viral posts ever?
2. Which authors post most consistently?
3. What % of posts are stories vs comments?
4. Which posts scored above average?
5. How does score vary by post type?
6. Who are top authors by total score?
7. Which year had the most posts?
8. How do posts break down by popularity tier?
9. Which authors are most consistent?
10. What % of posts are dead or deleted?
11. Which posts are true outliers?   
12. Where does virality drop off?      
13. Who are the reliable authors?      


## KEY INSIGHTS FROM HACKER NEWS ANALYSIS
=======================================

## BASIC ANALYSIS:
1. Stephen Hawking's death post = most viral ever (6015 upvotes)
2. Tech controversies & deaths dominate top posts
3. km is the most consistent author (avg 425 score per post)
4. Comments make up ~80% of all content on HN
5. Majority of posts score below 10 — going viral is RARE

## ADVANCED ANALYSIS:
6. Stephen Hawking post scored 439x above average — true All Time Legend
7. Biggest virality cliff = rank 3 to rank 4 (-1161 points / -20% drop)
8. Top 3 posts are in a completely different league from rank 4 onwards
9. Most "consistent" authors still have unpredictable score ranges
10. Reliability rank reveals km as the most dependable viral author

