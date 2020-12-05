# Climatechange Misinformation Detection

This project is to detect misinformation about climate change. Similar to fake news detection.

(Topic modeling and comparing distribution of topics) OR (supervised learning only on the misinformation label) may be considered for this kind of problem.

Here, the former approach was used but later expanded to LLDA (Labeled LDA), which can be trained as supervised learning with labels.

Using 1) LDA+W2V and 2) LLDA :
1. Topic modeling (LDA) and word vectors(W2V) and meta data (email, hashtag, etc.).
2. LLDA: supervised topic modelling (with labels)


Originally written in the google colab. Jupyter notebook codes here may be easier to see than colab codes:
1) LDA+W2V: https://colab.research.google.com/drive/1bLp7NvPLzTrmLfyhWPJY1iYi8sRTyvgB?usp=sharing
2) LLDA: https://colab.research.google.com/drive/1mGUZbmMBJJqgnRi0KwseViLcTTQy1NyV?usp=sharing
For LLDA, I borrowed most of the codes from someone who implemented LLDA class.
