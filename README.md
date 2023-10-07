# word2vec-id-wikipedia
## What is this
word2vec using custom windows size and custom datasets from wikipedia-id, this projecy are foccused on indonesia (ID) language only.

## Datasets used are bellow:
Source  : https://dumps.wikimedia.org/idwiki/latest/

File    : idwiki-latest-pages-articles.xml.bz2

## Pre-trained word2vec models (WIP)
Link: WIP

If you only want to use the pre-trained model for your project, you can use mine instead of manually training your own model. However, it's currently unavailable due to a cloud storage problem. Please stay tuned.

## How to use
Just place the datasets into datasets folder then follow the **main.ipynb** code

## Example of the project folder if the all files are uploaded
```
.
├── datasets
│   ├── idwiki-latest-pages-articles.xml.bz2
│   └── idwiki_new_lower.txt
├── main.ipynb
├── model
│   ├── idwiki_word2vec_200_skip-gram_window_2_new_lower.model
│   ├── idwiki_word2vec_200_skip-gram_window_2_new_lower.model.syn1neg.npy
│   └── idwiki_word2vec_200_skip-gram_window_2_new_lower.model.wv.vectors.npy
└── README.md

2 directories, 7 files
```
