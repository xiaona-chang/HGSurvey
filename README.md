# HGSurvey
>A collection of papers and resources related to Large Language Models.
>
>The organization of papers refers to our survey "Neural Headline Generation: A Comprehensive Survey".

## Summary of the models and frameworks used for headline generation tasks

|Strategy| Work |Code| Model Description | Learning Framework|
| ----------- |----------- |----------- | ----------- | ----------- |   
|Extractive | [MLRank[87]](https://aclanthology.org/C18-1148.pdf)|| Transformer+ Non-autoregressive | Seq2seq|
|Abstractive| [NACC[137]](https://proceedings.neurips.cc/paper_files/paper/2022/file/bb0f9af6a4881ccb6e14c11b8b4be710-Paper-Conference.pdf) |[[Code]](https://github.com/MANGA-UOFA/NACC)| Transformer+ Non-autoregressive | Seq2seq|	
|  | [NAUS[136]](https://arxiv.org/pdf/2205.14521) |[[Code]](https://github.com/MANGA-UOFA/NAUS)| Transformer+ Non-autoregressive	| Seq2seq|
|| [TI-C-NHG[171]](https://link.springer.com/article/10.1007/s11063-022-10942-2)  ||Transformer + Copy Mechanism	| Seq2seq|
| | [IT5[151]](https://pure.rug.nl/ws/portalfiles/portal/260396938/2203.03759.pdf) |[[Code]](https://github.com/gsarti/it5)  |T5	| Transfer Learning|
|	  | [Heng[57]](https://ieeexplore.ieee.org/abstract/document/9581133) | | UNILM	| Adversarial Learning |
|	  | [Amin et al.[91]](https://nahid.org/papers/c11.pdf)  || GRU + Attention | Seq2seq|
|	  | [Kanungo et al.[70]](https://aclanthology.org/2021.naacl-industry.33.pdf) | |MLM + Transformer |	Reinforcement Learning|
|	  | [SLGen[95]](https://ojs.aaai.org/index.php/AAAI/article/view/6501) | | GCN + GRU + Attention | Seq2seq|	
|	  | [DeepTitle[6]](https://arxiv.org/pdf/2107.10935)  || BERT |	Transfer Learning|
|	  | [HG-News[3]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9507422)  || GPT-2 + Pointer Network |	Transfer Learning|
|	  | [Matsushita et al.[94]](https://aclanthology.org/2021.ranlp-1.107.pdf)  || BART	| Transfer Learning|
|	  | [PENS[30]](https://aclanthology.org/2021.acl-long.7.pdf) |[[Code]](https://msnews.github.io/pens.html) | Transformer + Pointer Network	| Seq2seq|
|	  | [ZmBART[80]](https://arxiv.org/pdf/2106.01597)|| mBART	| Transfer Learning|
|	  | [Shavrina et al.[172]](https://www.elibrary.ru/item.asp?id=48123721#page=222)  || ruGPT-3	| Fine-tuning|
|	  | [CNHG[161]](https://ieeexplore.ieee.org/abstract/document/9142327) | |BiGRU + Attention |	Reinforcement Learning|
|	  | [Shu et al.[130]](https://pike.psu.edu/publications/icdm18.pdf) || Variational Auto-Encoder+RNN | Seq2seq|
|	  | [Littman et al.[144]](https://aclanthology.org/2020.figlang-1.pdf#page=54) | | BERT | Fine-tuning|
|	  | [Scarlatos et al.[67]](https://arxiv.org/pdf/2302.07974)|[[Code]](https://github.com/umass-ml4ed/mathGPT)| GPT-2 | Fine-tuning|
|	  | [Jang et al.[170]](https://aclanthology.org/2023.findings-eacl.159.pdf) | | Transformer | Adversarial Learning|
|Hybrid | [MuD2H[96]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9729734)  || GCN + BiLSTM | Seq2seq|	
| | [SHEG[5]](https://d1wqtxts1xzle7.cloudfront.net/94078423/s00521-020-05188-920221111-1-bf3m8-libre.pdf?1668194168=&response-content-disposition=inline%3B+filename%3DSHEG_summarization_and_headline_generati.pdf&Expires=1719991467&Signature=JSD4x8vQa6q~x2v1gqZRiWT9fPAOD5AL64zKyyJOlnkSVoWDjxfZYWQwG2mwjJ00vOkzsC61XCeSik1Qi66Sqdeo9XAWZGxDf8O~yOU5W3ZfSo~HXDZTY42~1LO09Gzwfha4hfrHU602NjS5XX0KaVa3hiYqTUln4C0ilxtEj7IJ26HkZTxlZdjLoUDv8yeWv6H7rOAJkjqsE-XIxPgBZze-gmgVbk5yvkWVzxQA2PBu-QiLlebhc42M23JDeFeWwnBWhdU5pMUfIzsncLnE3D8ISUNaJy-SfW0DRMdWOQX3ybYz~FrdgZYweMcrTmV6pKxGWD3gjAmQ926MaBWgiQ__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA) | | GRU + CNN + BiLSTM | Seq2seq|	
| | [Song et al.[104]](https://ojs.aaai.org/index.php/AAAI/article/view/6421) || BiLSTM	| Reinforcement Learning|
| | [Liu et al.[78]](https://aclanthology.org/W19-8904.pdf)  || BERT	| Transfer Learning|


## Summary of style infusion strategies for headline generation tasks
|Methods| Work |Code| Description | Style|
| ----------- | ----------- |----------- |----------- | ----------- |   
|Pre-processing|  [Littman et al.[144]](https://aclanthology.org/2020.figlang-1.pdf#page=54) | | Construct datasets | Satirical  |   
||[Lorenzo et al.[127]](https://aclanthology.org/2020.lrec-1.828.pdf)  || Train on style datasets |   |  
|In-process|[Zhan et al.[173]](https://www.ijcai.org/proceedings/2022/0623.pdf)  || Multi-task learning|
||  [Song et al.[104]](https://ojs.aaai.org/index.php/AAAI/article/view/6421)  ||Popularity classifier |Attractive|
|| [TitleStylist[10]](https://arxiv.org/pdf/2004.01980) |[[Code]]( https://github.com/jind11/TitleStylist) |Multi-task learning |Clickbait|
||[Li et al.[74]](https://ojs.aaai.org/index.php/AAAI/article/view/17565)  ||Style constraints module |Attractive|
|| [Shu et al.[130]](https://pike.psu.edu/publications/icdm18.pdf)   ||Style discriminator |Clickbait|
||[Xu et al.[8]](https://arxiv.org/pdf/1909.03582)  ||Reinforce learning | Clickbait  |   
|Post-processing|[Alnajjar et al.[9]](https://arxiv.org/pdf/2109.08702) ||Word replacement   |  Humor  |   
||[Stegeren et al.[1]](https://ris.utwente.nl/ws/files/124571222/vanstegeren2019churnalist.pdf) ||Word replacement  |  |   
|| [Alnajjar et al.[77]](https://helda.helsinki.fi/server/api/core/bitstreams/b0ed750c-a5c1-4bfd-a2ef-c2ed4fa04b90/content) ||Headline replacement  |Metaphorical   |   
||[Fu et al.[193]](https://ojs.aaai.org/index.php/AAAI/article/view/11330)  || Style transfer model |   |   
