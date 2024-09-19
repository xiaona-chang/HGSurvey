# HGSurvey
>A collection of papers and resources related to Large Language Models.
>
>The organization of papers refers to our survey "Neural Headline Generation: A Comprehensive Survey".
>
## Taxonomy of the headline generation tasks
|Taxonomy| |Work |Code| 
| ----------- |----------- |----------- |----------- |
|Application|News|[HG-News](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9507422)||
|||[Multi-HG](https://export.arxiv.org/pdf/2004.03875)|[Code](https://github.com/dayihengliu/KeyMultiHeadline)|
|||[Heng et al.](https://ieeexplore.ieee.org/document/9581133)||
||Paper|[Putra](https://www.researchgate.net/publication/322119181_Automatic_Title_Generation_in_Scientific_Articles_for_Authorship_Assistance_A_Summarization_Approach)||
|||[Elmnet](https://link.springer.com/article/10.1007/s11042-021-11641-1)||
||Email|[Nguyen et al.](https://www.researchgate.net/publication/360930536_AI_Gives_You_a_Good_Beginning)||
|||[Xue et al.](https://link.springer.com/chapter/10.1007/978-3-030-63820-7_76)||
|||[Zhang et al.](https://aclanthology.org/P19-1043.pdf)||
||Review|[Amplayo](https://aclanthology.org/D19-1562.pdf)|[Code](https://github.com/rktamplayo/CHIM)|
|||[Liu et al.](https://dl.acm.org/doi/10.1007/978-3-030-01716-3_27)||
||List|[Doh et al.](https://arxiv.org/pdf/2110.07354)||
||Questions|[Yuan et al.](https://arxiv.org/pdf/1912.00839)||
|||[Doh et al.](https://arxiv.org/abs/2110.07354)||
|||[Lit et al.](https://ieeexplore.ieee.org/document/9533288/)||
||Ad|[Kanungo et al.](https://dl.acm.org/doi/pdf/10.1145/3534678.3539069)||
|Summary Content|Indicative|[Wang et al.]()||
|	  || [Shu et al.](https://pike.psu.edu/publications/icdm18.pdf) ||
|	 | | [Littman et al.](https://aclanthology.org/2020.figlang-1.pdf#page=54) | |
|	 | | [Scarlatos et al.](https://arxiv.org/pdf/2302.07974)|[[Code]](https://github.com/umass-ml4ed/mathGPT)| |
|	  || [Jang et al.](https://aclanthology.org/2023.findings-eacl.159.pdf) | | | Adversarial Learning|
||Informative|[Yamada et al.]()||
|||[Takase et al.]()||
||Eyecatchers|[Alnajjar et al.](https://arxiv.org/pdf/2109.08702)||
|||[Jin et al.](https://arxiv.org/pdf/2004.01980)|[Code](https://github.com/jind11/TitleStylist)|
|||[Hossain et al.](https://aclanthology.org/N19-1012.pdf)||
|||[Alnajjar et al.](https://arxiv.org/pdf/2109.08702) | |   
|||[Stegeren et al.](https://ris.utwente.nl/ws/files/124571222/vanstegeren2019churnalist.pdf) 
||| [Alnajjar et al.](https://helda.helsinki.fi/server/api/core/bitstreams/b0ed750c-a5c1-4bfd-a2ef-c2ed4fa04b90/content) |   |   
|||[Fu et al.](https://ojs.aaai.org/index.php/AAAI/article/view/11330)  | | 
|Controllable generation|Faithfulness|[Matsumaru et al.](https://aclanthology.org/2020.acl-main.123.pdf)||
|||[Song et al.](https://arxiv.org/pdf/2002.02095)||
|||[Chu et al.](https://dl.acm.org/doi/10.1145/3366424.3382676)||
||Formal|[Zhang et al.](https://dl.acm.org/doi/10.1145/3269206.3271711)||
|||[Hitomi et al.](https://aclanthology.org/W19-8641.pdf)||
|||[Liu et al.](https://arxiv.org/pdf/2205.14522)|[Code](https://github.com/MANGA-UOFA/NACC)|
|||[Kanungo et al.](https://dl.acm.org/doi/pdf/10.1145/3534678.3539069)||
||Style|[Li et al.](https://arxiv.org/pdf/2012.07419)||
|| | [Song et al.](https://ojs.aaai.org/index.php/AAAI/article/view/6421)  ||
|| |[TitleStylist](https://arxiv.org/pdf/2004.01980) |[Code]( https://github.com/jind11/TitleStylist) |
|||[Li et al.](https://ojs.aaai.org/index.php/AAAI/article/view/17565)  ||
|| |[Shu et al.](https://pike.psu.edu/publications/icdm18.pdf)   ||
|||[Xu et al.](https://arxiv.org/pdf/1909.03582)  | | 
||Bias|[Chen et al.](https://aclanthology.org/W18-6509.pdf)||
|||[Lin et al.](https://ieeexplore.ieee.org/document/9457821)||
|Language|Mono-lingual|[Ao et al.](https://aclanthology.org/2021.acl-long.7.pdf)|[Code](https://paperswithcode.com/paper/pens-a-dataset-and-generic-framework-for)|
||Multi-lingual|[Alnajjar et al.](https://helda.helsinki.fi/bitstream/handle/10138/303715/iccc_proceedings_2019_258.pdf?sequence=1)||
|||[Liu et al.](https://aclanthology.org/W19-8904.pdf)||
|||[Martinc et al.](https://aclanthology.org/2022.lrec-1.381.pdf)||
||Cross-lingual|[Dorr et al.](https://dl.acm.org/doi/abs/10.1145/979872.979878)||
|||[Shen et al.](https://nlp.csai.tsinghua.edu.cn/~lzy/publications/taslp2018_zero.pdf)||
|||[Maurya et al.](https://aclanthology.org/2021.findings-acl.248.pdf)||
||Mixed-lingual|[Lit et al.](https://ieeexplore.ieee.org/document/9533288/)||
|||[Rallabandi et al.](https://www.cs.cmu.edu/~awb/papers/IS17_rallabandi.pdf)||


## Summary of the models and frameworks used for headline generation tasks

|Strategy| Work |Code| Model Description | Learning Framework|
| ----------- |----------- |----------- | ----------- | ----------- |   
|Extractive | [MLRank](https://aclanthology.org/C18-1148.pdf)|| Transformer+ Non-autoregressive | Seq2seq|
|Abstractive| [NACC](https://proceedings.neurips.cc/paper_files/paper/2022/file/bb0f9af6a4881ccb6e14c11b8b4be710-Paper-Conference.pdf) |[[Code]](https://github.com/MANGA-UOFA/NACC)| Transformer+ Non-autoregressive | Seq2seq|	
|  | [NAUS](https://arxiv.org/pdf/2205.14521) |[[Code]](https://github.com/MANGA-UOFA/NAUS)| Transformer+ Non-autoregressive	| Seq2seq|
|| [TI-C-NHG](https://link.springer.com/article/10.1007/s11063-022-10942-2)  ||Transformer + Copy Mechanism	| Seq2seq|
| | [IT5](https://pure.rug.nl/ws/portalfiles/portal/260396938/2203.03759.pdf) |[[Code]](https://github.com/gsarti/it5)  |T5	| Transfer Learning|
|	  | [Heng](https://ieeexplore.ieee.org/abstract/document/9581133) | | UNILM	| Adversarial Learning |
|	  | [Amin et al.](https://nahid.org/papers/c11.pdf)  || GRU + Attention | Seq2seq|
|	  | [Kanungo et al.](https://aclanthology.org/2021.naacl-industry.33.pdf) | |MLM + Transformer |	Reinforcement Learning|
|	  | [SLGen](https://ojs.aaai.org/index.php/AAAI/article/view/6501) | | GCN + GRU + Attention | Seq2seq|	
|	  | [DeepTitle](https://arxiv.org/pdf/2107.10935)  || BERT |	Transfer Learning|
|	  | [HG-News](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9507422)  || GPT-2 + Pointer Network |	Transfer Learning|
|	  | [Matsushita et al.](https://aclanthology.org/2021.ranlp-1.107.pdf)  || BART	| Transfer Learning|
|	  | [PENS](https://aclanthology.org/2021.acl-long.7.pdf) |[[Code]](https://msnews.github.io/pens.html) | Transformer + Pointer Network	| Seq2seq|
|	  | [ZmBART](https://arxiv.org/pdf/2106.01597)|| mBART	| Transfer Learning|
|	  | [Shavrina et al.](https://www.elibrary.ru/item.asp?id=48123721#page=222)  || ruGPT-3	| Fine-tuning|
|	  | [CNHG](https://ieeexplore.ieee.org/abstract/document/9142327) | |BiGRU + Attention |	Reinforcement Learning|
|	  | [Shu et al.](https://pike.psu.edu/publications/icdm18.pdf) || Variational Auto-Encoder+RNN | Seq2seq|
|	  | [Littman et al.](https://aclanthology.org/2020.figlang-1.pdf#page=54) | | BERT | Fine-tuning|
|	  | [Scarlatos et al.](https://arxiv.org/pdf/2302.07974)|[[Code]](https://github.com/umass-ml4ed/mathGPT)| GPT-2 | Fine-tuning|
|	  | [Jang et al.](https://aclanthology.org/2023.findings-eacl.159.pdf) | | Transformer | Adversarial Learning|
|Hybrid | [MuD2H](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9729734)  || GCN + BiLSTM | Seq2seq|	
| | [SHEG](https://d1wqtxts1xzle7.cloudfront.net/94078423/s00521-020-05188-920221111-1-bf3m8-libre.pdf?1668194168=&response-content-disposition=inline%3B+filename%3DSHEG_summarization_and_headline_generati.pdf&Expires=1719991467&Signature=JSD4x8vQa6q~x2v1gqZRiWT9fPAOD5AL64zKyyJOlnkSVoWDjxfZYWQwG2mwjJ00vOkzsC61XCeSik1Qi66Sqdeo9XAWZGxDf8O~yOU5W3ZfSo~HXDZTY42~1LO09Gzwfha4hfrHU602NjS5XX0KaVa3hiYqTUln4C0ilxtEj7IJ26HkZTxlZdjLoUDv8yeWv6H7rOAJkjqsE-XIxPgBZze-gmgVbk5yvkWVzxQA2PBu-QiLlebhc42M23JDeFeWwnBWhdU5pMUfIzsncLnE3D8ISUNaJy-SfW0DRMdWOQX3ybYz~FrdgZYweMcrTmV6pKxGWD3gjAmQ926MaBWgiQ__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA) | | GRU + CNN + BiLSTM | Seq2seq|	
| | [Song et al.](https://ojs.aaai.org/index.php/AAAI/article/view/6421) || BiLSTM	| Reinforcement Learning|
| | [Liu et al.](https://aclanthology.org/W19-8904.pdf)  || BERT	| Transfer Learning|


## Summary of style infusion strategies for headline generation tasks
|Methods| Work |Code| Description | Style|
| ----------- | ----------- |----------- |----------- | ----------- |   
|Pre-processing|  [Littman et al.](https://aclanthology.org/2020.figlang-1.pdf#page=54) | | Construct datasets | Satirical  |   
||[Lorenzo et al.](https://aclanthology.org/2020.lrec-1.828.pdf)  || Train on style datasets |   |  
|In-process|[Zhan et al.](https://www.ijcai.org/proceedings/2022/0623.pdf)  || Multi-task learning|
||  [Song et al.](https://ojs.aaai.org/index.php/AAAI/article/view/6421)  ||Popularity classifier |Attractive|
|| [TitleStylist](https://arxiv.org/pdf/2004.01980) |[[Code]]( https://github.com/jind11/TitleStylist) |Multi-task learning |Clickbait|
||[Li et al.](https://ojs.aaai.org/index.php/AAAI/article/view/17565)  ||Style constraints module |Attractive|
|| [Shu et al.](https://pike.psu.edu/publications/icdm18.pdf)   ||Style discriminator |Clickbait|
||[Xu et al.](https://arxiv.org/pdf/1909.03582)  ||Reinforce learning | Clickbait  |   
|Post-processing|[Alnajjar et al.](https://arxiv.org/pdf/2109.08702) ||Word replacement   |  Humor  |   
||[Stegeren et al.](https://ris.utwente.nl/ws/files/124571222/vanstegeren2019churnalist.pdf) ||Word replacement  |  |   
|| [Alnajjar et al.](https://helda.helsinki.fi/server/api/core/bitstreams/b0ed750c-a5c1-4bfd-a2ef-c2ed4fa04b90/content) ||Headline replacement  |Metaphorical   |   
||[Fu et al.](https://ojs.aaai.org/index.php/AAAI/article/view/11330)  || Style transfer model |   |   
