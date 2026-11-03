## Adding DACCS to the PyPSA-Eur Belgium Tutorial

How does the integration of cardon dioxide removal (CDR) into the EU ETS affect emissions abatement?

While there are many things to take into account to answer this question, the following notebook is designed to simply begin with DACCS (Direct Air Carbon Capture and Storage) integration into a simple PyPSA-Eur electricity system example.

This notebook goes through the following:

1. Establishing a baseline electricity system in Belgium via the PyPSA-Eur tutorial: https://pypsa-eur.readthedocs.io/en/latest/tutorial/

2. Calculating baseline operational CO2 emissions.

3. Lowering the carbon emissions cap and recalculating the baseline system. 

4. Adding DACCS as a load. 

5. Analyze the impact on electricity generation and net emissions.
