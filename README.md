# Long Document Summarization

This document provides a comprehensive summary of several research papers related to the topic of Long Document Summarization, with a specific focus on experiments conducted using the BillSum dataset.

**Models and Dataset**

| Full name                                                                 | Paper                                              | Summary
| ------------------------------------------------------------------------- |:--------------------------------------------------:|:-------------------------------------:|
| Longformer: The Long-Document Transformer                                 | https://arxiv.org/pdf/2004.05150              | [Longformer](https://github.com/ducdinhchu/long-document-summarization/blob/main/S_Longformer.pdf)
| LongT5: Efficient Text-To-Text Transformer <br> for Long Sequences        | https://arxiv.org/pdf/2112.07916              | [LongT5](https://github.com/ducdinhchu/long-document-summarization/blob/main/S_LongT5.pdf)
| TextRank: Bringing Order into Texts                                       | https://aclanthology.org/W04-3252           | [TextRank](https://github.com/ducdinhchu/long-document-summarization/blob/main/S_TextRank.pdf)
| LexRank: Graph-based Lexical Centrality as Salience <br> in Text Summarization | https://arxiv.org/abs/1109.2128                   | [LexRank](https://github.com/ducdinhchu/long-document-summarization/blob/main/S_LexRank.pdf)
| BillSum: A Corpus <br> for Automatic Summarization of US Legislation      | https://arxiv.org/pdf/1910.00523             | [BillSum](https://github.com/ducdinhchu/long-document-summarization/blob/main/S_BillSum.pdf)
| A Discourse-Aware Attention Model <br> for Abstractive Summarization of Long Documents | https://arxiv.org/pdf/1804.05685       | [arXiv, PubMed](https://github.com/ducdinhchu/long-document-summarization/blob/main/S_arXiv_PubMed.pdf)


# Results

<p align="center">
<img src="https://github.com/ducdinhchu/long-document-summarization/blob/main/results.jpg?raw=true" alt="Kết quả thử nghiệm" width="65%">
</p>

A summary of results for long document summarization using the BillSum dataset is presented. DOC, SUM, and DOC + SUM are from the original BillSum paper. As of July 2023, the LED large model leads the pack. The last three are my implementations, with LEDopt standing out as the top performer.
