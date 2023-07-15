# Introduce

This notebook compare's **feature importances** which are created between cuml and sklearn RandomForestClassifiers

Feature importances calculated in sklearn needs to use ```RandomForestClassifier().feature_importances_```, while in cuml needs to use [this function](https://github.com/rapidsai/cuml/issues/3531#issuecomment-1100623350) with one line fixed.

# Requirements

python == 3.10

[rapids](https://docs.rapids.ai/install) == 23.06

scikit-learn == 1.3.0

matplotlib == 3.7.2 (optional)
