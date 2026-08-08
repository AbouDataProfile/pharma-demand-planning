# MedCore Pharma — Demand Planning Intelligence
# Core dependencies for notebooks 01 through 06

pandas>=2.0
numpy>=1.24
matplotlib>=3.7
seaborn>=0.13
scikit-learn>=1.3
statsmodels>=0.14
xgboost>=2.0
jupyter>=1.0

# Note: Prophet was evaluated for M4 (forecast models) but excluded due to a Python 3.13 / Stan / cmdstanpy compatibility issue on Windows. Not included 
# here, see M4 notebook for details. Holt-Winters (statsmodels) was used as the substitute.

# sqlite3, os, random, and warnings are part of the Python standard Library and do not need to be installed separately.
