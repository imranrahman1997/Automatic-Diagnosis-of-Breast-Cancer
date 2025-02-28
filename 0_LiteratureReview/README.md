Description
This academic competition has the aim to accopmany students through the Machine Learning in Healthcare course at the University School for Advanced Studies IUSS Pavia.

The target of the copmetition is to implement a model able to automatically discriminate malignant from benign lesions in breast ultrasound (US) studies.

The dataset and rules of submission are briefly described in the corresponding sections of this hosting page.


Evaluation
User submissions are evaluated by comparing their Submission CSV to the ground truth Solution CSV with respect to the Area Under the ROC Curve (AUC) metric.

The Submission CSV file must contain a prediction score or probability for each classified study, corresponding to the probability of that lesion(s) to belong to class "Malignant" or "Benign".

It is expected that the probability to belong to class "Benign" ranges from 0 to 0.5, and that the probability to belong to class "Malignant" ranges from 0.5 to 1 (p < 0.5 -> "Benign", p > 0.5 -> "Malignant").
