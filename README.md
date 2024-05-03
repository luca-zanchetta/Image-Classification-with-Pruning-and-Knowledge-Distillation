# Image-Classification-with-Pruning-and-Knowledge-Distillation

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/12ifrATuHpV7yMQj9BM_qPuy1rS5Ebjy5?usp=drive_link)

In this notebook, I briefly present some funny experiments I have done during my free time at the beginning of my Master Thesis work. In particular, the aim of these experiments was to state whether:
1. The Knowledge Distillation technique actually performs better than a full training, starting from a given model;
2. The performance of the student model trained with the help of a pruned version of the teacher is greater than that of the 'classic' student model.

Results show that:
1. In general, a student model performs better than an identical model which has not been trained by applying knowledge distillation;
2. A student model trained on a pruned version of the teacher can outperform the student model trained by applying the classical knowledge distillation technique. However, in this case, the performance heavily depends on the adopted pruning strategy.
