Milestone 2: Model Building

This branch contains all deliverables related to Milestone-2 and the associated datasets

Building a model architecture which can classify.
Trying different model architectures by researching state of the art for similar tasks.
Train the model
To deal with large training time, save the weights so that you can use them when training the model for the second time without starting from scratch.
Description of the files are as given below

Transformer_no_att_no_hyp : Encoder-decoder(transformer) without attention and no hyperparameter tuning

Transformer_no_att_hyp : Encoder-decoder(transformer) without attention and hyperparameter tuning(learning rate and batch size)

Attention_no_hyp : Encoder-decoder(transformer) with attention mechanism and no hyperparameter tuning

Attention_hyp : Encoder-decoder(transformer) with attention mechanism and hyperparameter tuning

cp_dl : Lstm,Bilstm,Gru and BiGru without hyperparameter tuning

cp_dl_hyp : Lstm,Bilstm,Gru and BiGru with hyperparameter tuning

Bert-Transformers - uses BERT as the non trainable base model plus CNN

GPT2-Transformers2 - uses GPT 2 as the non trainable base model plus CNN

cp-nlp-FeatureEngg* - various notebooks use different Feature Engg techniques on ML & DL models

capstone-nlp-DL-GlOve-BILSTM* - uses BILST with Hyper Param tuning

capstone_nlp_ML_Model_interpretation - Demos ELI5 to interpet an LR model.

The models have been built on 3 differents kinds of data

a) Unaugmented data

b) Level 1 augmented data

c) Level 2 augmented data
