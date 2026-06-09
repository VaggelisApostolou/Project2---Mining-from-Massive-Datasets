# Project2---Mining-from-Massive-Datasets
Semester project for "Mining from Massive Datasets" course from "Data and Web Science" Master's (Aristotle University of Thessaloniki)

The notebook was developed in Google Colab
Important!!! SAND is currently incompatible with NumPy 2.x. After executing the first installation cell, restart the runtime/session before continuing.
In Google Colab: Runtime → Restart Session and then execute the notebook starting from the second code cell. Failure to restart the session may cause import errors when loading the SAND implementation.

How to run:

1)Run the first notebook cell

2)Restart the runtime/session and continue execution from the second cell and below (as mentioned above).

3)Run all the rest cells sequentially

The following datasets from TSB-UAD are used (you need to upload them in the “contents” section in Google Colab):
•
genesis-anomalies.test.csv@3.out from GENESIS
•
D-15.test.out from NASA-MSL
•
machine-1-1.test.csv@20.out from SMD
The notebook automatically creates:
•
Normality_1.csv (GENESIS)
•
Normality_2.csv (GENESIS, NASA-SML)
•
Normality_3.csv (GENESIS, NASA-SML, SMD)

The notebook also produces visualization plots for dataset visualization, offline baselines, SAND evaluation, streaming variants.
Notes: Random seed is fixed (random_state=42) where applicable. Also, small differences in Autoencoder results may occur due to TensorFlow training randomness.
