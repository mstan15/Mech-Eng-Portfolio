# Mech-Eng-Portfolio
My (Mitchell Stankey) body of work as a mechanical engineer.  This README contains a brief and general overview of my mechanical and systems design experience.  More detailed presentations of my work are included in this repository.

Printed Circuit Board (PCB)/Circuit Card Assembly (CCA) Design:
  - Component, laminate, pre-preg, soldermask, and silkscreen selection to meet UL flammability and electrical requirements.
  - Overall dimensions, isolation distances, and pin spacing to satisfy IEC 61010 creepage and clearance rules.
  - Add slot cutouts to enable high voltage isolation and prevent flux leakage.
  - Strain relief features to maintain PCB stiffness.
  - Shielding features for electromagnetic interference (EMI).

Cable Harness Design: 
  - Component selection to meet flammability, electrical, galvanic, and mating frequency requirements.
  - Wire length chosen to give +10% service loop to given cable run.
  - Strain relief added as necessary to maintain cable position and wire conductor and jacket integrity.
  - High voltage cables ordered through UL wiring harness program supplier to verify the cable meets both UL construction and electrical requirements.

Thermal V&V
  - Use an IR camera to determine hot spots, analyze bill of materials (BOM) of the device under test (DUT) to identify component temperature limits.
  - Work with electrical engineers to determine power dissipation.
  - Work with software engineers to write a program(s) based on expected use cases that will thermally stress the DUT.
  - Instrument components of the DUT with thermocouples according to previously gathered information.
    - Instrument intakes and general exhaust regions.
    - Properly strain relieve thermocouples.
  - Run the DUT and log thermal data.
  - Analyze the data to find rise over ambient temperature value, use that value to determine the DUT's operating temperature.
