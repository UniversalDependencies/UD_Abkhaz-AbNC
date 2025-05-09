# Summary

UD_Abkhaz-AbNC is a treebank based on texts from the Abkhaz National Corpus, [AbNC](https://clarino.uib.no/abnc).

# Introduction

UD_Abkhaz-AbNC is a treebank based on texts from the Abkhaz National Corpus, [AbNC](https://clarino.uib.no/abnc), which is a corpus of written texts from a variety of genres. The sentences are taken from a collection of fairy tales for children (Аҧсуа лакәқәа – Ахәыҷқәа рзы, editor: Мықәба, А.), a short story by Валентин Дбар and other literary texts.

The sentences are analysed using a finite state morphological analyser, and Constraint Grammar rules for disambiguation and dependency parsing. Both disambiguation and dependency analyses are corrected manually in a tool specifically developed for that purpose.

## Compatibility with the AbNC

In the Abkhaz National Corpus, a proprietary annotation scheme for lemma forms and morpho-syntactic features is used. The AbNC annotations, from which the UD annotations are derived, are kept in the UD analyses: the original lemma form can be found in the MISC column as value of the LMSeg attribute; the morpho-syntactic features are available in the XPOS column.

# Acknowledgments

The Abkhaz treebank and the tools used to create it have been developed by Paul Meurer.

I am grateful to Saida Adzhindzhal (Suchum) for helping me understanding some of the constructions in the texts.

## References

* Paul Meurer. A finite state approach to Abkhaz morphology and stress. Lecture Notes in Computer Science 2011, Volume 6618. pp. 271-282.
* Paul Meurer. The Abkhaz National Corpus. Proceedings of the Eleventh International Conference on Language Resources and Evaluation (LREC 2018), Miyazaki, Japan 2018. pp. 2456–2460.
* Paul Meurer. [Towards a Treebank of Abkhaz. The AbNC, Analysing Abkhaz, and the Importance of Good Tools](https://doi.org/10.62235/dk.2.2023.7477). Digital Kartvelology, Volume II (2023). 

# Changelog

* 2025-05-15 v2.16
  * Added sentences to a total of 1221
  * Splitting off copula as separate token
* 2024-11-15 v2.15
  * Added sentences to a total of 853
  * Changed Trans=Yes/No to Subcat=Tran/Intr
* 2024-05-15 v2.14
  * Initial release in Universal Dependencies, 263 sentences


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.14
License: CC BY-SA 4.0
Includes text: yes
Genre: fiction
Lemmas: converted from manual
UPOS: converted from manual
XPOS: manual native
Features: converted from manual
Relations: manual native
Contributors: Meurer, Paul
Contributing: elsewhere
Contact: paul.meurer@uib.no
===============================================================================
</pre>
