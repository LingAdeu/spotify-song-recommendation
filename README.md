![header](header.png)

# Lyric-Based Spotify Song Recommendation Model 

## About
My current project explores the implementation of different vector embedding techniques, covering both static and contextual embeddings with Word2Vec (Mikolov et al., [2013](https://arxiv.org/pdf/1301.3781) and an Indonesian variant of Bidirectional Encoder Representations from Transformers (IndoBERT, Koto et al., [2020](https://arxiv.org/pdf/2011.00677)). My intention for exploring both embedding techniques are not to compare their performance, e.g., which technique can better represent nuanced in song lyrics and which one is more optimized. Instead, I would like to demonstrate that to build a song recommender system, both embedding techniques can be done, and a static embedding technique like Word2Vec is sufficient for the task. In the real-world scenario, while this static embedding cannot capture nuanced in the lyrics, Word2Vec performs faster in generating vectors, speeding up the process of the machine learning flow.

## Folder Organization
    .
    ├── README.md                     <- The top-level README for using this project.
    └── notebook
        ├── notebook-BERT.ipynb       <- Jupyter notebook file for  modeling: BERT
        └── notebook-word2vec.ipynb   <- Jupyter notebook file for modeling: Word2Vec

## Feedback
If there are any questions or suggestions for improvements, feel free to contact me here:

<a href="https://www.linkedin.com/in/adelia-januarto/" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg" width="52" height="40" alt="linkedin logo"/>
  </a>
<a href="mailto:januartoadelia@gmail.com" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/gmail/default.svg"  width="52" height="40" alt="gmail logo"/>
  </a>
