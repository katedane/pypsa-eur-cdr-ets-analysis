## Adding DACCS to the PyPSA-Eur Belgium Tutorial
The following notebook is designed as a proof of concept for integrating DACCS (Direct Air Carbon Capture and Storage) into a simple PyPSA-Eur electricity system example and analyzing emissions reductions with DACCS.

This notebook goes through the following:

1. Establishing a baseline electricity system in Belgium via the PyPSA-Eur tutorial: https://pypsa-eur.readthedocs.io/en/latest/tutorial/

2. Calculating baseline operational CO2 emissions.

3. Lowering the carbon emissions cap and recalculating the baseline system.

4. Integrating DACCS as a load into the network.

5. Compare the CO2 emissions before and after DACCS integration.
