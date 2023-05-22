# npl-fp-2023

_The final project of the Natural Language Processing course._

____
**Theme:** Song lyrics generation within a specified genre

**Author:** Melihedov Artem
____


### Abstract

From the very beginning of work in the field of text generation, one of the directions was the direction associated with the creation of works of art: poems, stories, songs. After the developments in the field of text generation for musical works achieved some success, researchers began to complicate the generation process with additional conditions, such as text subject matter, rhythmic pattern, generation based on a musical fragment, etc. This work explores the possibility of generating lyrics within a given genre. During the implementation of the project, 2 generative models (LSTM as a baseline and GPT-2) and a classifying model (BERT) were trained (finetuned) to assess belonging to the genre.

#### Dataset

To build dataset scraped lyrics from Vagalume was used. This dataset was made by scrapping data from Vagalume website. It contains 371182 song lyrics from 4168 artist in 79 different musical genres and in different languages. For this work we used only english songs with 5 most popular genres: Pop, Rock, Hip Hop, R\&B, Rap.


#### Models 

Thre models was used in this work:

- LSTM text generating model;
- GPT-2 generating model;
- BERT classification model.


#### Files

- NLP_FP_2023.pdf - project report;
- nlp_2023_final_project.ipynb - main notebook;
- README.md - this file.
