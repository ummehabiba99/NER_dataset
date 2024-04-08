# CoNLL 2003 Dataset

This dataset contains labeled named entity recognition (NER) data in the CoNLL 2003 format. The dataset includes sentences with corresponding annotations for words, part-of-speech (POS) tags, and named entity tags.

## File Format

The dataset is provided in a CSV format with the following columns:

- **Sentence #**: The sentence number.
- **Word**: The word in the sentence.
- **POS**: The part-of-speech tag for the word.
- **Tag**: The named entity tag for the word.

Each sentence is represented as a sequence of words with their corresponding POS and named entity tags.

## Example

```
Sentence #,Word,POS,Tag
Sentence: 1,Thousands,NNS,O
,of,IN,O
,demonstrators,NNS,O
,have,VBP,O
,marched,VBN,O
,through,IN,O
,London,NNP,B-geo
,to,TO,O
...
```

## Usage

This dataset can be used for training and evaluating NER models. It provides labeled data that can be used to develop models to recognize named entities in text.

## Citation

If you use this dataset in your work, please cite the original source:

CoNLL 2003 shared task: Language-independent named entity recognition. Tjong Kim Sang E F, De Meulder F. Proceedings of CoNLL-2003. 2003.

---
