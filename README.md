# jobtitle_to_function_challenge

## Workflow
- Input File : titles.txt
- Output File: 'Job_titles\_with\_func\_\&\_level.txt'

- Wordcloud for Unigrams and Bigrams
  - WordCloud_for_frequent_words.png
  - WordCloud_Bigrams_frequent_words.png
  
- Lookup : lookups.ipynb (update categories, functions, levels, 'abbrevations')
  Saved_files:
  - abbv_transforms.pkl
  - Job_Functions.pkl
  - Job_Levels.pkl
  
- Run/Analyse job_title_to_function.ipynb (jupyter notebook)

- Future_Work
  - Using n-gram model improve lookups by creating new job_function, job_levels 
  - Need to create labelled dataset(label first 100)
  - Plot High Dimensional Vectors(t-sne, LDA,CMDS)
  - Analyze Word Embedding and supervised/unsupervised clustering
  - **Integrate ONET database for SOC codes and other features(Work Functions, Role Description)**
