# Conceptual Model Clustering: A Relator-Centric Approach <br>Supplementary Materials

This repository contains supplementary materials for the research paper (under review):

Guizzardi, G., Sales, T. P., Almeida, J. P. A., & Poels, G. (2021). **Conceptual Model Clustering: A Relator-Centric Approach**. Software and Systems Modeling.

In the paper, we report on an empirical experiment in which conceptual modeling experts express their preferences for different modularization strategies.

Here you will find the material related to this experiment:

* The dataset containing the answers to the survey ([answers.csv](/answers.csv))
* The survey forms used in the experiment

PS: This dataset is completely anonymied, as we did not collect any information that could be used uncover the identity of the participants.

## Dataset

The columns in [answers.csv](/answers.csv) are interpreted as follows:

* **Subject**: A number that identifies the subject who answered the survey
* **Survey**: A string that identifies which of the 3 variants of the survey the subject answered. Possible values are:
  * `ABC`, 
  * `IJK`, and 
  * `XYZ`.
* **Experience in conceptual modeling**: A string that identifies how much experience the subject declared to have in conceptual modeling. Possible values:
  * `0 to 4 years`,
  * `4 to 8 years`, and
  * `More than 8 years`
* **Knowledge of conceptual modeling languages**: A string containing a list of conceptual modeling languages the subject declared to have knowledge of. May contain, but is not limited to, the following values:
  * `Unified Modeling Language (UML)`
  * `OntoUML`
  * `(Extended) Entity Relationship (ER)`
  * `Object-Role Modeling (ORM)`
  * `SysML`
* **Expertise**: A string indentifying how much of an expert in conceptual modeling the subject considered herself/himself to be. Possible values:
  * `Novice`
  * `Intermediate`
  * `Expert`
* **Current position**: A string identifying the current professional position held by the subject. May contain, but is not limited to, one of the following values:
  * `BSc-level student`
  * `MSc-level student`
  * `PhD-level student`
  * `Post-doctoral researcher`
  * `Professor`
  * `Business analyst / architect`
  * `System analyst / expert`
  * `Software engineer`
  * `Other IT staff position`
  * `Other business function`
  * `Middle or senior level manager`
* **Relator-centric (Rank)**: A number identifying the how the subject ranked the [Relator-centric modularization approach](https://doi.org/10.1007/978-3-030-63479-7_15). Possible values:
  * `1 (best)`
  * `2`
  * `3 (worst)`
* **Relator-centric (Rank)**: A number identifying the how the subject ranked [Akoka and Comyn-Wattiau’s modularization approach](https://doi.org/10.1016/S0169-023X(96)00007-9). Possible values:
  * `1 (best)`
  * `2`
  * `3 (worst)`
* **Castano (Rank)**: A number identifying the how the subject ranked [Castano et al.’s modularization approach](https://doi.org/10.1145/293910.293150). Possible values:
  * `1 (best)`
  * `2`
  * `3 (worst)`

## Authors

* [Giancarlo Guizzardi](http://www.inf.ufes.br/~gguizzardi/), Conceptual and Cognitive Modeling Research Group (CORE), Free University of Bozen-Bolzano, Bolzano, Italy
* [Tiago Prince Sales](https://www.inf.unibz.it/~tpsales/), Conceptual and Cognitive Modeling Research Group (CORE), Free University of Bozen-Bolzano, Bolzano, Italy
* [João Paulo A. Almeida](https://nemo.inf.ufes.br/equipe/jpalmeida/), Ontology & Conceptual Modeling Research Group (NEMO), Federal University of Espírito Santo, Vitória, Brazil
* [Geert Poels](https://www.mis.ugent.be/author/gpoels/), UGent Business Informatics Research Group, Ghent University, Ghent, Belgium
