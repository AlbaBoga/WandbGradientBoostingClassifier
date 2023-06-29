# Gradient Boosting Classifier
[Enlace](https://api.wandb.ai/links/alba-m-boga/xfstxrbi)

Utilización del modelo Gradient Boosting Classifier y un dataset de Vino para clasificar el vino en función de sus componentes químicos, a partir de la herramienta Wandb.

## Hiperparámetros para iniciación del modelo

* Learning rate: [0.01,0.15,0.5]
* Maximum depth: [2,3,5]
* n estimators: [100,125,150]
* Loss functions: Deviance
* Subsamples: [0.4,0.8,1]
* Minimum samples split: [2,4,6]
* Minimum samples leafs: [1,2,3]

## Mejor calificación

* El modelo: gbm_lr0.01_depth5_est125_lossdeviance_subsample1_minsplit2_minleaf3
* Score: 0.9815
* Learning rate: 0.01
* Maximum depth: 2
* Minimum samples leaf: 3
* Minimum samples split: 2
* n_estimators: 100
* Subsample:0.4
* Loss functions: Deviance

## Número de experimentos

* Se han realizado 214 experimentos.
* Mean score: 0.9593
