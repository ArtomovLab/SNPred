# SNPred
Ensemble SNV pathogenicity prediction tool.

## About SNPred
SNPred is an ensemble model for classification of nonsynonymous single nucleotide variants (nsSNVs) pathogenicity. It utilizes 33 pathogenicity scores, 7 conservation score and allele frequencies from gnomAD and ExAC to make an aggregate prediction. SNPred is based on CatBoost v1.2 implementation of gradient boosting. SNPred's training data comprised ClinVar variants added before January, 2022.

## SNPred scores
SNPred scores for all possible nsSNVs are available at https://www.synapse.org/#!Synapse:syn52137034/files/

## Running SNPred from Python
```SNPred_get_scores.ipynb``` provides code for obtaining SNPred scores for a list of variants. To quickly get feature matrix ```myvariant``` library is used to make requests to dbNSFP.
