bilingual-nigerian-chatbot/
├── .gitignore
├── README.md
├── requirements.txt
├── config.yaml
├── data/
│   ├── raw/
│   │   ├── pidgin_conversations.jsonl
│   │   └── ibibio_seed_translations.jsonl
│   └── processed/
│       ├── train.jsonl
│       └── val.jsonl
├── notebooks/
│   └── colab_t4_finetuning.ipynb
├── src/
│   ├── __init__.py
│   ├── data_loader.py
│   ├── preprocess.py
│   └── train.py
└── app/
    ├── __init__.py
    ├── main.py
    └── templates/
        └── index.html
