---
title: "Programming Projects"
permalink: /projects/
---

**Project:** _scikit-learn_<br/>
**Date:** 2025-2026<br/>
**Summary:** [scikit-learn](https://scikit-learn.org) is a Python package for all sorts of machine learning applications.<br/>
**My role in it:** Starting October 2025, I will assist the scikit-learn maintainers with the general maintenance of the project and the development of new features.<br/>
**Links:** tbd

-----

**Project:** Refactoring the _clembench_ framework<br/>
**Date:** September - December 2024<br/>
**Summary:** The [clembench framework]((https://clembench.github.io/)) is designed to evaluate Large Language Models (such as the GPTs and other open or commercially available models) by letting them play language games against each other.<br/>
**My role in it:** I initiated the refactoring of the code to separate the specific games from the framework. This paved the way to make the framework a separate module and allowed for easier addition of new games.<br/>
**Links:** [Code](https://github.com/AnneBeyer/clembench/commits/game_registry/?before=4c43cc760b854c712aaa84de86c2fd35d5d7303f+35)

-----

**Project:** Exploring entity status in contextual word embeddings<br/>
**Date:** 2022<br/>
**Summary:** My colleague and I set out to explore if current language models encode (i.e., "know") whether an entity (like an object or person) was already mentioned before in the context, wich is essential for knowing how to refer to it ("_the_ book" assumes that we already know which book we are talking about, whereas "_a_ book" can be used to introduce a new one).<br/>
**My role in it:** I implemented a classifier that took the contextualized word representations from a model and used it to predict whether the corresponding entity was known or new in the given context.<br/>
**Links:** [Code](https://github.com/clp-research/new-old-discourse-entities/blob/main/classification/entity_classifier.py), [Paper](https://aclanthology.org/2022.coling-1.73/)

------

**Project:** Introduction to _huggingface_ <br/>
**Date:** August 2022<br/>
**Summary:** Together with some colleuagues I designed and gave a workshop on Deep Learning for linguists within the [CRC 1287](https://www.sfb1287.uni-potsdam.de/en/)<br/>
**My role in it:** I set up and guided participants through a jupyter notebook for using models from the [huggingface](https://huggingface.co/) library (as it was in August 2022)<br/>
**Links:** [Notebook](https://annebeyer.github.io/assets/Using_pre-trained_models_with_Python.ipynb)