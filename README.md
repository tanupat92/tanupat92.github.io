# auroc-auprc.github.io

The Problem with Class Imbalance
In medicine, most patients are healthy (the "negative" class), and only a few have the specific disease you're looking for (the "positive" class). This is called a class imbalance. The interactive demonstration below will show you how this imbalance affects our evaluation metrics.

- AU-ROC (Area Under the Receiver Operating Characteristic Curve): This measures how well the model separates positive and negative classes. It's robust, but it can look overly optimistic when you have a lot of healthy patients.
- AU-PRC (Area Under the Precision-Recall Curve): This measures the trade-off between a model's precision (how many positive predictions are correct) and its recall (how many actual positives were found). It is highly sensitive to class imbalance and is often a more informative metric for tasks like clinical screening.