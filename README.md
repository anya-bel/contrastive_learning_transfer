# Enhancing token-level representations in PLMs using contrastive learning : a cross-model and cross-language study

This is the repository with the code and datasets used to fine-tune pre-trained language models as described in the TALN paper: [Raffinage des représentations des tokens dans les modèles de langue pré-entraînés avec l’apprentissage contrastif : une étude entre modèles et entre langues](https://coria-taln-2025.lis-lab.fr/wp-content/uploads/2025/06/CORIA-TALN_2025_paper_139.pdf).

### Usage

The codebase is located in the `code` folder which links to the repository from our paper, introducing the supervised contrastive fine-tuning approach ([Injecting Wiktionary to improve token-level contextual representations using contrastive learning](https://aclanthology.org/2024.eacl-short.5/)). Please, refer to that repository to launch the training.


### Content

`Datasets` folder contains sixteen files:

**French datasets**

* Verb
 * `french_wikt_verb_train_set.csv` is the train set of the Wiktionary dataset for French verbs * `french_wikt_wic_verb_dev.csv` is the development part of the Wiktionary dataset in Word-in-Context format * `french_wikt_wic_verb_test.csv` is the test part of the Wiktionary dataset in Word-in-Context format* `french_xl_wic_dev_modified.csv` is the development part of the [XL-WiC](https://pilehvar.github.io/xlwic/) dataset (French part)* `french_xl_wic_test.csv` is the test part of the [XL-WiC](https://pilehvar.github.io/xlwic/) dataset (French part)

**English datasets**

* Verb
 *  `english_wikt_verb_train_set.csv` is the train set of the Wiktionary dataset for English verbs
 * `english_wikt_wic_verb_dev.csv` is a development part of the English Wiktionary dataset for verbs in the Word-in-Context format
 * `english_wikt_wic_verb_test.csv` is a test part of the English Wiktionary dataset for verbs in the Word-in-Context format


* Noun
 * `english_wikt_noun_train_set.csv` is the train set of the Wiktionary dataset for English nouns
 * `english_wikt_wic_noun_dev.csv` is a development part of the Wiktionary dataset for English nouns in the Word-in-Context format
 * `english_wikt_wic_noun_test.csv` is a test part of the Wiktionary dataset for English nouns in the Word-in-Context format

* Adjective
 * `english_wikt_adj_train_set.csv` is the train set of the Wiktionary dataset for English adjectives
 * `english_wikt_wic_adj_dev.csv` is a development part of the Wiktionary dataset for English adjectives in the Word-in-Context format
 * `english_wikt_wic_adj_test.csv` is a test part of the Wiktionary dataset for English adjectives in the Word-in-Context format


* `original_wic_dev_set.csv` is a development part of the original [WiC dataset](https://pilehvar.github.io/wic/)
* `original_wic_test_set.csv` is a test part of the original [WiC dataset](https://pilehvar.github.io/wic/)
  