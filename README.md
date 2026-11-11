# Multiple Myeloma Survival Prediction

This project compares machine learning approaches for estimating survival time in a multiple myeloma dataset with missing features and censored observations. The experiments use cross-validation and a mean squared error metric that accounts for censoring.

The Python notebooks start with a linear regression baseline, compare nonlinear models and imputation methods, and use Isomap to learn a lower-dimensional representation from labelled and unlabelled data. The final model uses ridge regression to combine predictions from several tree-based models.

Developed by Edgar Cucubica, Joana Wang, and Renato Viola.

[Experiment notebooks](Code/) · [Results presentation](ML%40NOVA%20Egas%20%26%20Juju%20%26%20D%C3%A9d%C3%A9.pdf)
