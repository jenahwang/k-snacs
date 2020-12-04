# K-SNACS Dataset and Guidelines
**Korean Semantic Network of Adposition and Case Supersense**

## Dataset: Little Prince

**File:** little_prince_ko.tsv

**Column Description:**
* doc_id: chapter number, starts at 1
* sent_id: sentence id, starts at 1
* token_id: token id, starts 1. Stacked postpositions receive token_id-N designation, where N is a sequencial value starting at 1 (as an example see doc_id 1, sent_id 14, token_id 1).
* form: token raw form
* morph: morphological analysis obtained from KOMA Tagger (REF). 
* p: postposition
* gold_scene: gold adjudicated scene role label
* gold_function: gold adjudicated function label

## Guidelines


## Paper
Please cite the following when using this data:

> Hwang, Jena D., Hanwool Choe, Na-Rae Han, and Nathan Schneider. "K-SNACS: Annotating Korean adposition semantics." In Proceedings of the Second International Workshop on Designing Meaning Representations. 2020. 

[Hwang et al., 2020](https://www.aclweb.org/anthology/2020.dmr-1.6/)