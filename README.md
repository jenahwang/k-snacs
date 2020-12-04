# K-SNACS Dataset and Guidelines
**Korean Semantic Network of Adposition and Case Supersense**

## Dataset: Little Prince

**File:** little_prince_ko.tsv

**Column Description:**
* <tt>doc_id</tt>: chapter number, starts at 1
* <tt>sent_id</tt>: sentence id, starts at 1
* <tt>token_id</tt>: token id, starts at 1. Stacked postpositions receive token_id-N designation, where N is a sequencial value starting at 1 (as an example see doc_id 1, sent_id 14, token_id 1).
* <tt>form</tt>: word form
* <tt>morph</tt>: morphological analysis obtained from [KOMA Tagger](https://ieeexplore.ieee.org/document/5075772). 
* <tt>p</tt>: postposition
* <tt>gold_scene</tt>: gold adjudicated scene role label
* <tt>gold_function</tt>: gold adjudicated function label

## Guidelines


## Paper
Please cite the following when using this data:

> Hwang, Jena D., Hanwool Choe, Na-Rae Han, and Nathan Schneider. "K-SNACS: Annotating Korean adposition semantics." In Proceedings of the Second International Workshop on Designing Meaning Representations. 2020. 

[Hwang et al., 2020](https://www.aclweb.org/anthology/2020.dmr-1.6/)