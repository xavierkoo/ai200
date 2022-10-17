# Facebook Human or Robot Kaggle Competition
TLDR: Machine Learning project to determine whether online bids made on an auction site were from humans or bots.

Kaggle Link: https://www.kaggle.com/competitions/ai200-dec-2021-human-or-bot/overview

## Project Particulars

### Aim
The project aim was to determine whether online bids made on an auction site were from humans or bots. Analyzed more than 7 million online auction bids and trained an ensemble model by performing feature engineering in Python to classify the bids as done by humans or robots.

Private Score: 0.87067

Public Score: 0.86828

## Tech Stack 
* Python

## Features Selected
'auction', 'device', 'time', 'country', 'ip', 'url', 'bids_per_auc', 'log_bids_per_auc', 'url_per_auc', 'log_url_per_auc', 'ips_per_auc', 'log_ips_per_auc', 'bids_per_dev', 'log_bids_per_dev', 'bids_per_country', 'log_bids_per_country', 'bids_per_ip', 'log_bids_per_ip', 'bids_per_url', 'log_bids_per_url', 'num_bids', 'log_num_bids', 'num_instant_counts', 'log_counts', 'response_difference', 'log_difference', 'change_ip_freq', 'log_change_ip_freq', 'countries_per_auc', 'log_countries_per_auc', 'bids_entropy_per_ip', 'log_bids_entropy_ip', 'bids_entropy_per_url', 'log_bids_entropy_url', 'bids_entropy_country', 'log_bids_entropy_country', 'log_url', 'log_auction', 'log_device', 'log_time', 'log_country', 'log_ip'

## Machine Learning Models
Used stratified K-Fold to compare the results of different models. CatBoostClassifier, RandomForestClassifier, ExtraTreesClassifier and AdaBoostClassifier. Decided to settle on RandomForestClassifier.
