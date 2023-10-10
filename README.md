# word2vec-id-wikipedia
## What is this
word2vec using custom windows size and custom datasets from wikipedia-id, this projecy are foccused on indonesia (ID) language only.

## Datasets used are bellow:
Source  : https://dumps.wikimedia.org/idwiki/latest/

File    : idwiki-latest-pages-articles.xml.bz2

## Pre-trained word2vec models

If you only want to use the pre-trained model for your project, you can use mine instead of manually training your own model.

**Always Verify What You Download**

Compare what you download with the **md5sum** that i put on the download link

Link: https://mega.nz/folder/6y5XXY6K#mjaEBjGBETEWrYuL13hS_Q

## How to use
Just place the **datasets** into **datasets** folder then follow the **main.ipynb** code

## Example of the project folder 
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

## Posible Error Found:
```
TypeError: __randomstate_ctor() takes from 0 to 1 positional arguments but 2 were given
```
### Fix
https://stackoverflow.com/questions/75490275/gensim-pickle-error-enable-to-load-the-saved-topic-model

## Contact Me
Telegram: @shadow1graves