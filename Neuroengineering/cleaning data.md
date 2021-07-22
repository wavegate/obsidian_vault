[[scaling]]
- helps gradient descent converge more quickly
- helps avoid the "NaN trap", in which one number in the model becomes a NaN and causes every other number in the model to also eventually become a NaN
-

handling extreme outliers
- one way is to take log
- you can also cap or clip off values at an arbitrary value

binning