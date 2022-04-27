# Simple TICO-19

Simple TICO-19 is a language resource that provides manual simplifications for the English and Spanish portions of the [TICO-19](https://tico-19.github.io/index.html) dataset for Machine Translation of COVID-19 content.
Our goal is to contribute to research on joint machine translation and text simplification, as well as monolingual text simplification in the medical domain.

This repository includes:

- A [dataset](dataset) with nearly 6,000 original-simplified sentence pairs, corresponding to the development and test splits of the TICO-19 benchmark, for English and Spanish;
- The [annotation guidelines](AnnotationGuidelines.pdf) designed for our expert annotators to simplify original sentences in a monolingual setting;
- [Scripts](scripts) to analyse the simplification instances included in the dataset in terms of readability improvement and simplification operations performed.


## Licence

Simple TICO-19 is released under a [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) licence.

## Citation

If you use Simple TICO-19 in your research, please cite [Simple TICO-19: A Dataset for Joint Translation and Simplification of COVID-19 Texts]() (Shardlow & Alva-Manchego, LREC 2022).


> Matthew Shardlow and Fernando Alva-Manchego. 2022. [Simple TICO-19: A Dataset for Joint Translation and Simplification of COVID-19 Texts](). In *Proceedings of the 13th Language Resources and Evaluation Conference*, Marseille, France. European Language Resources Association.


```
@inproceedings{shardlow-alva-manchego-2022-simple,
    title = "Simple {TICO}-19: A Dataset for Joint Translation and Simplification of COVID-19 Texts",
    author = "Shardlow, Matthew and 
      Alva-Manchego, Fernando",
    booktitle = "Proceedings of the 13th Language Resources and Evaluation Conference",
    month=jun,
    year = "2022",
    address = "Marseille, France",
    publisher = "European Language Resources Association",
    language = "English",
}
```