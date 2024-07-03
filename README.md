# HGSurvey
>A collection of papers and resources related to Large Language Models.
>
>The organization of papers refers to our survey "Neural Headline Generation: A Comprehensive Survey".

## Summary of the models and frameworks used for headline generation tasks

|Strategy| Work | Model Description | Learning Framework|
| ----------- | ----------- | ----------- | ----------- |   
|Extractive | MLRank| Transformer+ Non-autoregressive | Seq2seq|
|Abstractive| NACC | Transformer+ Non-autoregressive | Seq2seq|	
|  | NAUS   | Transformer+ Non-autoregressive	| Seq2seq|
|| TI-C-NHG  |Transformer + Copy Mechanism	| Seq2seq|
| | IT5  |T5	| Transfer Learning|
|	  | Heng  | UNILM	| Adversarial Learning |
|	  | Amin et al.  | GRU + Attention | Seq2seq|
|	  | Kanungo et al. | MLM + Transformer |	Reinforcement Learning|
|	  | SLGen  | GCN + GRU + Attention | Seq2seq|	
|	  | DeepTitle  | BERT |	Transfer Learning|
|	  | HG-News  | GPT-2 + Pointer Network |	Transfer Learning|
|	  | Matsushita et al.  | BART	| Transfer Learning|
|	  | PENS  | Transformer + Pointer Network	| Seq2seq|
|	  | ZmBART  | mBART	| Transfer Learning|
|	  | Shavrina et al.  | ruGPT-3	| Fine-tuning|
|	  | CNHG | BiGRU + Attention |	Reinforcement Learning|
|	  | Shu et al. | Variational Auto-Encoder+RNN | Seq2seq|
|	  | Littman et al.  | BERT | Fine-tuning|
|	  | Scarlatos et al.| GPT-2 | Fine-tuning|
|	  | Jang et al.  | Transformer | Adversarial Learning|
|Hybrid | MuD2H  | GCN + BiLSTM | Seq2seq|	
| | SHEG  | GRU + CNN + BiLSTM | Seq2seq|	
| | Song et al. | BiLSTM	| Reinforcement Learning|
| | Liu et al.  | BERT	| Transfer Learning|
			
