# Supplementary information
 Notebooks and files from the paper "De novo Design and Bioactivity Prediction of SARS-CoV-2 Main Protease Inhibitors using Recurrent Neural Network-based Transfer Learning"

## [data/](https://github.com/marcossantanaioc/De_novo_design_SARSCOV2/tree/master/data)

**Generative models data**
- [AID_1706_misc_combined_processed.zip](https://github.com/marcossantanaioc/De_novo_design_SARSCOV2/blob/master/data/AID_1706_misc_combined_processed.zip): data used to train the generative model and classifier

- [ChEMBL_v1.zip](https://github.com/marcossantanaioc/De_novo_design_SARSCOV2/blob/master/data/ChEMBL_v1.zip): ChEMBL data used to train the general chemical model

**Classifier data**
- [external_validation_mpro_xchem.csv](https://github.com/marcossantanaioc/De_novo_design_SARSCOV2/blob/master/data/external_validation_mpro_xchem.csv): external validation set of fragments screened against SARS-CoV-2 Mpro
- [random_splits.tar.gz](https://github.com/marcossantanaioc/De_novo_design_SARSCOV2/blob/master/data/random_splits.tar.gz): Random splits used to train the classifier
- [scaffold_splits.tar.gz](https://github.com/marcossantanaioc/De_novo_design_SARSCOV2/blob/master/data/scaffold_splits.tar.gz): Scaffold-based split used to train the classifier

## [notebooks/](https://github.com/marcossantanaioc/De_novo_design_SARSCOV2/blob/master/notebooks)

**ULMFit notebook**
- [LSTM_generative.ipynb](https://github.com/marcossantanaioc/De_novo_design_SARSCOV2/blob/master/notebooks/LSTM_generative.ipynb): notebook used for ULMFit.

## [models/](https://github.com/marcossantanaioc/De_novo_design_SARSCOV2/blob/master/models)

**General chemical model**
- [general_model_weights.pth](https://github.com/marcossantanaioc/De_novo_design_SARSCOV2/blob/master/models/general_model_weights.pth): Pretrained weights of the general chemical model.
- [vocab.pkl](https://github.com/marcossantanaioc/De_novo_design_SARSCOV2/blob/master/models/vocab.pkl): Chemical vocabulary of the general chemical model. This vocabulary is necessary to fine-tune the model.

**Fine-tuned model**
- [finetuned_encoder.pth](https://github.com/marcossantanaioc/De_novo_design_SARSCOV2/blob/master/models/finetuned_encoder.pth): Encoder (all layers except the last one) of the fine-tuned chemical model
- [finetuned_model.pkl](https://github.com/marcossantanaioc/De_novo_design_SARSCOV2/blob/master/models/finetuned_model.pkl): Fine-tuned chemical model
- [classifier.pkl](https://github.com/marcossantanaioc/De_novo_design_SARSCOV2/blob/master/models/classifier.pkl): Final fine-tuned classifier



