# Simple TICO-19

Simple TICO-19 is a language resource that provides manual simplifications for the English and Spanish portions of the [TICO-19](https://tico-19.github.io/index.html) dataset for Machine Translation of COVID-19 content.
Our goal is to contribute to research on joint machine translation and text simplification, as well as monolingual text simplification in the medical domain.


![Picture showing an example of a translation and simplification instance in the dataset](https://user-images.githubusercontent.com/2760680/173864779-2c8f020c-6d4c-4b80-b7f7-fe2344e133d4.png)


This repository includes:

- A [dataset](dataset) with nearly 6,000 original-simplified sentence pairs, corresponding to the development and test splits of the TICO-19 benchmark, for English and Spanish;
- The [annotation guidelines](AnnotationGuidelines.pdf) designed for our expert annotators to simplify original sentences in a monolingual setting;
- [Scripts](scripts) to analyse the simplification instances included in the dataset in terms of readability improvement and simplification operations performed.


## Licence

Simple TICO-19 is released under a [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) licence.

## Citation

If you use Simple TICO-19 in your research, please cite our LREC 2022 paper:

> Matthew Shardlow and Fernando Alva-Manchego. 2022. [Simple TICO-19: A Dataset for Joint Translation and Simplification of COVID-19 Texts](http://www.lrec-conf.org/proceedings/lrec2022/pdf/2022.lrec-1.331.pdf). In *Proceedings of the 13th Language Resources and Evaluation Conference*, pages 3093-3102, Marseille, France. European Language Resources Association.


```BibTeX
@inproceedings{shardlow-alva-manchego-2022-simple,
    title = "Simple {TICO}-19: A Dataset for Joint Translation and Simplification of COVID-19 Texts",
    author = "Shardlow, Matthew and 
      Alva-Manchego, Fernando",
    booktitle = "Proceedings of the 13th Language Resources and Evaluation Conference",
    month=jun,
    year = "2022",
    address = "Marseille, France",
    publisher = "European Language Resources Association",
    url = "http://www.lrec-conf.org/proceedings/lrec2022/pdf/2022.lrec-1.331.pdf",
    pages = "3093--3102",
    abstract = "Specialist high-quality information is typically first available in English, and it is written in a language that may be difficult to understand by most readers. While Machine Translation technologies contribute to mitigate the first issue, the translated content will most likely still contain complex language. In order to investigate and address both problems simultaneously, we introduce Simple TICO-19, a new language resource containing manual simplifications of the English and Spanish portions of the TICO-19 corpus for Machine Translation of COVID-19 literature. We provide an in-depth description of the annotation process, which entailed designing an annotation manual and employing four annotators (two native English speakers and two native Spanish speakers) who simplified over 6,000 sentences from the English and Spanish portions of the TICO-19 corpus. We report several statistics on the new dataset, focusing on analysing the improvements in readability from the original texts to their simplified versions. In addition, we propose baseline methodologies for automatically generating the simplifications, translations and joint translation and simplifications contained in our dataset.",
}
```
