# Determining the Distance to Galaxy NGC 1068: Cepheid Star Analysis
Astronomy Assignment/Project — Determining Galaxy Distance.
Analysis of brightness data from Cepheid variable star candidates (stars that pulsate and change brightness regularly) to determine the distance to the NGC 1068 galaxy. This analysis

has two main goals:
Calculate the absolute distance of the galaxy from Earth in Megaparsecs (Mpc). Build a Period-Luminosity Relationship graph (a graph comparing the star's pulsation time with its brightness) to ensure the data matches physical theory.

Findings:
- The distance to the NGC 1068 galaxy was successfully calculated as 11.35 Mpc.
- The distance modulus (a number showing the difference between the brightness we see and its actual brightness) is $\mu=30.274$ magnitudes.
- There are 42 Cepheid stars used in this calculation, all confirmed to have a pulsation period of over 19.5 days.

Brief Method
- Load the CSV table data and clean the text data. This step removes symbols that cannot be calculated mathematically to leave clean numbers.
- Fix label errors in the data columns. The visual light (F555W) and infrared (F814W) columns that were swapped in the original data are corrected to their right positions.
- Calculate the Wesenheit Magnitude (W_I). This is a formula for measuring star brightness that has been corrected to be free from the dimming effects of space dust.
- Calculate the final distance iteratively using constants from scientific literature.
- Create a scatter plot. The horizontal axis is the logarithm of the period (P) and the vertical axis is W_I. A red line (best fit) is drawn to show the data matching trend.

A full explanation of each step and the physics formulas used can be found in the notebook code comments.
The notebook requires the data file Cepheid Candidates in NGC 1068.csv to run. Make sure this file is downloaded and placed in the same folder as the notebook before running it.
