Take for example {'Charleston Road', 'North Shoreline Boulevard'} for a feature called street_name
We use feature engineering to convert strings to numeric values
We take these feature values and refer to them as the **vocabulary** and all other values to an **OOV (out of vocabulary) bucket**
so we can map Charleston Road to 0, map North Shoreline Boulevard to 1
However, 0 and 1 have no meaning.. they are just indexes. We don't want to give a weight to 0 and 1. We want to give a weight to each string that is encoded by the 0 and 1, 2, etc.
We also can't account for multiple values of street names
To deal with this, we can create a binary vector