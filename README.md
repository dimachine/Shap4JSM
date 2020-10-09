# Shap4JSM

This repository contains a demo code and data on Shapley values for JSM-method in terms of Concept Lattices (FCA) presented in the paper:

* [Dmitry I. Ignatov, Léonard Kwuida: Interpretable Concept-Based Classification with Shapley Values. ICCS 2020: 90-102](https://doi.org/10.1007/978-3-030-57855-8_7).

**Abstract**

*Among the family of rule-based classification models, there are classifiers based on conjunctions of binary attributes. For example, JSM-method of automatic reasoning (named after John Stuart Mill) was formulated as a classification technique in terms of intents of formal concepts as classification hypotheses. These JSM-hypotheses already represent interpretable model since the respective conjunctions of attributes can be easily read by decision makers and thus provide plausible reasons for model prediction. However, from the interpretable machine learning viewpoint, it is advisable to provide decision makers with importance (or contribution) of individual attributes to classification of a particular object, which may facilitate explanations by experts in various domains with high-cost errors like medicine or finance. To this end, we use the notion of Shapley value from cooperative game theory, also popular in machine learning. We provide the reader with theoretical results, basic examples and attribution of JSM-hypotheses by means of Shapley value on real data.*


It also continues our work on interpretable contribution of attributes to concept stability values:

* [Dmitry I. Ignatov, Léonard Kwuida: Shapley and Banzhaf Vectors of a Formal Concept. CLA 2020: 259-271](http://ceur-ws.org/Vol-2668/paper20.pdf).

The associated repository also contains a demo code and data: https://github.com/dimachine/ShapStab/.

To acknowledge use of the code and data in publications, please cite the following papers and mention this repository.

## References

1. 
```bibtex
@inproceedings{Ignatov:2020b,
  author    = {Dmitry I. Ignatov and
               L{\'{e}}onard Kwuida},
  editor    = {Mehwish Alam and
               Tanya Braun and
               Bruno Yun},
  title     = {Interpretable Concept-Based Classification with Shapley Values},
  booktitle = {Ontologies and Concepts in Mind and Machine - 25th International Conference
               on Conceptual Structures, {ICCS} 2020, Bolzano, Italy, September 18-20,
               2020, Proceedings},
  series    = {Lecture Notes in Computer Science},
  volume    = {12277},
  pages     = {90--102},
  publisher = {Springer},
  year      = {2020},
  url       = {https://doi.org/10.1007/978-3-030-57855-8\_7},
  doi       = {10.1007/978-3-030-57855-8\_7},
}
```

2. 
```bibtex
@inproceedings{Ignatov:2020a,
  author    = {Dmitry I. Ignatov and
               L{\'{e}}onard Kwuida},
  editor    = {Francisco J. Valverde{-}Albacete and
               Martin Trnecka},
  title     = {Shapley and Banzhaf Vectors of a Formal Concept},
  booktitle = {Proceedings of the Fifthteenth International Conference on Concept
               Lattices and Their Applications, Tallinn, Estonia, June 29-July 1,
               2020},
  series    = {{CEUR} Workshop Proceedings},
  volume    = {2668},
  pages     = {259--271},
  publisher = {CEUR-WS.org},
  year      = {2020},
  url       = {http://ceur-ws.org/Vol-2668/paper20.pdf},
}
```


