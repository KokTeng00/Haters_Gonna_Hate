# Haters Gonna Hate: A Gender-Based Analysis of Online Discourse on Pop Artists


## Project Overview

This project investigates gender-based differences in online discourse, focusing on toxicity and sexual explicitness in comments about male and female pop artists on Reddit. By analyzing comments related to the top 10 male and female artists from the 2023 Billboard Global charts, the study aims to uncover how the nature and themes of these discussions vary by gender.

## Key Components

- **Data Collection**: We gathered Reddit comments and submissions related to the top 10 male and female artists using data from Academic Torrents. 
- **Toxicity and Sexual Explicitness Detection**: We employed Google’s Perspective API to evaluate the levels of toxicity and sexual explicitness in the comments.
- **Topic Modeling**: Using both Latent Dirichlet Allocation (LDA) and BERTopic integrated with Llama2-chat 7B, we identified and analyzed the key themes in discussions surrounding male and female artists.

## Main Findings

- **Gender-Based Differences**: Female artists receive more sexually explicit comments, whereas male artists are more frequently subjected to toxic comments.
- **Topic Diversity**: Discussions around female artists cover a broader range of topics, including appearance and personal life, while male artist discussions are more focused on music and career-related topics.

## Repository Structure

- `DataCollectionPreprocessing.ipynb`: Notebook for data collection and preprocessing.
- `Significant Testing (Comment Analysis).ipynb`: Notebook containing the analysis of comment toxicity and sexual explicitness.
- `Topic Modeling (BERTopic integrated with Llama2).ipynb`: Notebook for topic modeling using BERTopic with Llama2.
- `outputs/`: Directory containing output files including model results.
- `loaded_data/`: Directory with the processed data used in the analysis.
- `female_parameter_performance.txt` & `male_parameter_performance.txt`: Files detailing the performance metrics of models used for analyzing female and male artist data, respectively.



## Authors

- Shmaila Ahmad
- Minjeong Lee
- Nathalie Möck
- Kok Teng Ng
- Seoyoung Yoo
- Xinwen Zou
