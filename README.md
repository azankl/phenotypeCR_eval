# Evaluation and Finetuning of Phenotype Concept Recognition Tools

Repo for UNSW Capstone Project P106 - Evaluation and Finetuning of Phenotype Concept Recognition Tools

The goal of this project is to evaluate the performance of SOTA Phenotype Concept Recognition tools like [PhenoTagger](https://github.com/ncbi-nlp/PhenoTagger) against our newly created HPO Phenotype Gold Corpus.

The Gold Corpus was created with [INCEpTION](https://inception-project.github.io). Text spans representing phenotypes were highlighted and labelled with a corresponding HPO term. See the [Annotation Guidelines](Annotation_Guidelines.pdf) for details.

The annotations were exported in [BioC](https://inception-project.github.io/releases/36.5/docs/user-guide.html#sect_formats_bioc) and [UIMA CAS JSON](https://inception-project.github.io/releases/36.5/docs/user-guide.html#sect_formats_uimajson) formats. See here for more on [BioC](https://bioc.sourceforge.net) and [UIMA](https://uima.apache.org/d/uimaj-current/tug.html).

To recreate the Gold Corpus in INCEpTION, import the file [Inception_Export.zip](Inception_Export.zip) into INCEpTION, see [here](https://inception-project.github.io/releases/36.5/docs/user-guide.html#_import) or Import instructions in the INCEpTION User Guide. Do *not* unzip the file before importing!
