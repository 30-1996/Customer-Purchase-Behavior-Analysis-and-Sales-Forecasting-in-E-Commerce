#📊 Online Shoppers Intention Dataset
This dataset contains information about user behavior on an e-commerce website during a specific session. The goal is to predict whether a user will generate revenue (i.e., make a purchase) based on various features related to their browsing behavior.

DATASET:-
Source:- UCI Machine Learning Repository
Instance:- 12330
🧾 Main Features:-
Administrative, Informational, ProductRelated: Number of pages visited in each category.

Administrative_Duration, Informational_Duration, ProductRelated_Duration: Total time spent on those pages.

BounceRates & ExitRates: Metrics indicating how often users leave the site after viewing only one page or after a specific page.

PageValues: Represents the value of the page from a revenue standpoint.

SpecialDay: Indicates closeness to a special day (e.g., Mother’s Day).

OperatingSystems, Browser, Region, TrafficType: Technical/user info.

VisitorType: Whether a user is returning or new.

Weekend: Boolean (converted to integer) indicating if the session happened on a weekend.

Revenue: Target variable — 1 if a purchase was made, 0 otherwise.

PREPROCESSING APPLIED:-
Converted boolean columns (Weekend, Revenue) to integers.

Encoded categorical variables (VisitorType, Month, etc.) using Label Encoding and one-hot encoding (get_dummies).

Scaled numerical features using StandardScaler.

Outlier detection was prepared using z-score (though not shown completely in the snippet).




