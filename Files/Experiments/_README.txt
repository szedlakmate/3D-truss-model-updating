The meaning of the file names is the following:
"lab" + load [g] + Long (opcionally) + clamping type

If the letter L (Long) is not written, then the length of the bar bas 665 mm. If it belongs to the long version, then the length was 893 mm.
The clamping has two types:
  perfect (A)
  partial (B)
  
The "Input data" files stores the following data:
[relative displacement], measuring time from time.time() function without formatting

The "UpdateResults" files stores the following data:
[relative displacement, updated inertia, updated clamping rigidity]
  [Inertia] = mm^4
  [clamping rigidity] = Nm/rad
  
The experiments were assisted with the attached truss_47_plate.py program. Please note that this version is in "nighty" state.
BEFORE RUNNING SIMULATIONS, always configure the truss_47_plate.py program as it is describe in the header of the file!

Please note that in lates versions the arduino_mapping.txt input was deprecated.