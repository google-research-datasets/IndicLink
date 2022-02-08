# IndicLink - KG Fact Linking Evaluation Dataset for Indian Languages

IndicLink is a KG Fact Linking dataset that has sentences and their corresponding linked KG facts from WikiData. 
The dataset is collected as part of the publication - [Multilingual Fact Linking](https://openreview.net/pdf?id=jbnn1iNNsUj) (AKBC'21). 
The sentences are present in English and six Indian languages - Hindi, Telugu, Tamil, Urdu, Gujarati and Assamese.
The descriptions of language-agnostic WikiData facts are also shared for the given languages.
The English sentences and their facts are taken from the test set of [WebRED](https://github.com/google-research-datasets/WebRED) and the sentences are translated into the different Indian languages by using the services of professional translators.

If you use this dataset, please cite:
```
@article{kolluru2021mfl,
    title={Multilingual Fact Linking}, 
    author={Keshav Kolluru and Martin Rezk and Pat Verga and William Cohen and Partha Talukdar},
    year={2021},
    journal={Automated Knowledge Base Construction (AKBC)}
}
```

The distribution of examples across different languages are as follows:

| IndicLink | English | Hindi | Telugu | Tamil | Urdu | Gujrati | Assamese |
|-----------|---------|-------|--------|-------|------|---------|----------|
|#Test Examples | 1002 | 889 | 888 | 881 | 1001 | 881 | 887 | 6429 | 
|#KG Facts | 4.6M | 230K | 145K | 248K | 361K | 91K | 257 | 4.6M |

The oracle set of 4.6 million KG facts correspond to all facts that occur in the top-1 million most frequent WikiData entities.
Their textual descriptions are always available in English but only sparsely available in other languages.

## License

This data is licensed by Google LLC under a [Creative Commons Attribution 4.0
International License](http://creativecommons.org/licenses/by/4.0/).
Users will be allowed to modify and repost it, and we encourage them to analyze
and publish research based on the data.


