# Midterm Project: Craigslist scraper for motorcycle listings in NY
This repo contains the functions and workflows required to scrape Craigslist motorcycle listings in New York, extract fields of interest using RegEx and LLM, compile the information, train a decision tree regressor, and sync all results back to Github. 

To run this workflow, you must clone this repo and set up your google cloud platform project (i.e, defining variables, enabling permissions, etc.). Once all functions and workflows are successfully deployed, predictions and permutation importance results will be synced back to the "results" and "perm_results" folders, respectively. The python file included in the "scripts" folder can be utilized to track model performance over time.  
