# Recognizing-hand-written-digits-using-PCA
Recognizing hand-written digits using PCA

## Get sklearn dataset
from sklearn.datasets import load_digits
digits = load_digits()

## Scale the dataset
from sklearn.preprocessing import StandardScaler
x_std =  StandardScaler().fit_transform(x)

## Find covariance matrix
using covariance matrix get eigrn values and the eigen vectors


##cumulative explained variance
cum_var_exp = np.cumsum(var_exp)

## Apply PCA
from sklearn.decomposition import PCA
