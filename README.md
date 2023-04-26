# CSE508 Information Retrieval Project - Winter 2023 semester

### Group 53
- Varun Khurana: 2019124
- Harsh Kumar: 2019043

### Directory structure
- ```baseline/```: baseline results
- ```mid/```: mid-semester project results
- ```final/```: final project results

### Data
```base_data``` = ```final/task/data/```
- JSON files (raw data) for videos from different domains -- news, education, podcasts, recipes and documentaries: ```{base_data}```
- Generated video transcript summaries: ```{base_data}/summary```
- Generated data of query-summary pairs: ```{base_data}/queries```

### Scripts
```base_src``` = ```final/task/src/```
#### Transcript Summarisation
- Baseline summarisation models: ```{base_src}/Baseline_Results_Summ.ipynb```
- LSTM-Attention model: ```{base_src}/LSTM_Attention_Summarisation.ipynb```

#### Video Retrieval using Deep Semantic Search
- Video retrieval baseline model: ```{base_src}/Video Search - FAISS.ipynb.ipynb```
- Video retrieval re-ranking model: ```{base_src}/Video Search - FAISS Rerank.ipynb```
- Quantitative evaluation of video retrieval: ```{base_src}/BEIR_Evaluation.ipynb```

### Models
```base_models``` = ```final/task/models/```
- Finetuned model weights: ```{base_models}/finetuned_model/```
- Finetuned model index: ```{base_models}/finetuned_faiss_index.index```
