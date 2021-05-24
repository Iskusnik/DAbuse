# DAbuse
Файл .data содержит данные с UCI: https://archive.ics.uci.edu/ml/datasets/Drug+consumption+%28quantified%29
E. Fehrman, A. K. Muhammad, E. M. Mirkes, V. Egan and A. N. Gorban, "The Five Factor Model of personality and evaluation of drug consumption risk.," arXiv [Web Link], 2015

Файлы Jupiter Notebook описывают процесс разработки моделей на основе этих данных.
1. AllParamsDAbVul.ipynb - модель бинарной классификации по отношению людей к наркозависимым на всех нелегальных веществах.
2. DrugAddictionVulnerability.ipynb - неудачные модели по классификации людей на основе их зависимости от метадона.


## Полученные модели
* nn_binary_classifier - модель Keras для бинарной классификации данных
* rf_binary_classifier - модель scikit-learn на основе случайного леса для бинарной классификации


