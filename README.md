# ML Labs Notebooks

Учебные работы по машинному обучению — практика с реальными алгоритмами и датасетами: от разведочного анализа данных до сверточных нейронных сетей и подбора гиперпараметров.

## Содержание

| № | Работа | Тема | Результат |
|---|--------|------|-----------|
| 01 | [Pandas EDA — Iris](./01-pandas-eda-iris) | Разведочный анализ данных, работа с pandas | — |
| 02 | [KNN (sklearn) — Breast Cancer](./02-knn-sklearn-breast-cancer) | Классификация опухолей, k-ближайшие соседи | Accuracy 0.93 |
| 03 | [KNN с нуля — Breast Cancer](./03-knn-from-scratch-breast-cancer) | Реализация KNN без sklearn | Accuracy 0.93 |
| 04 | [Простая линейная регрессия](./04-simple-linear-regression-skin-cancer) | Смертность от рака кожи vs широта | — |
| 05 | [Множественная линейная регрессия](./05-multiple-linear-regression-startup-profit) | Прогноз прибыли компаний | R² = 0.90 |
| 06 | [Логистическая регрессия — Churn](./06-logistic-regression-customer-churn) | Прогноз оттока клиентов | — |
| 07 | [Полиномиальная регрессия](./07-polynomial-regression-overfitting) | Переобучение при росте степени полинома | — |
| 08 | [MNIST — классификация цифр](./08-mnist-digit-classification-ann) | Полносвязная нейросеть | Accuracy 97.55% |
| 09 | [MNIST — устойчивость к шуму](./09-mnist-noise-robustness) | Влияние шума на качество модели | 97.69% → 67.58% → 82.99% |
| 10 | [CNN — CIFAR-10](./10-cnn-cifar10-image-classification) | Классификация изображений, свёрточные сети | Accuracy 70.78% |
| 11 | [Подбор гиперпараметров — Keras Tuner](./11-cnn-hyperparameter-tuning-keras-tuner) | Автоматический подбор архитектуры CNN | Val accuracy до 82% |
| 12 | [Аугментация данных — CIFAR-10](./12-cifar10-data-augmentation) | Улучшение обобщающей способности модели | Accuracy 72.07% |
| 13 | [Сила аугментации — сравнение](./13-cifar10-augmentation-strength-comparison) | Слабая / умеренная / усиленная аугментация | Accuracy 75.55% / 69.63% / 59.72% |

## Стек

Python, Pandas, NumPy, Scikit-learn, TensorFlow/Keras, Matplotlib, Seaborn, Keras Tuner
