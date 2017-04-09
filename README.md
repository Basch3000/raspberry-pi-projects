# raspberry-pi-projects
All kinds of small (python) scripts for the Raspberry Pi.

**motordeg.py usage**:

python motordeg.py [step_time] [degrees] [direction] [step_start]

**step_time**: 1 for fastest possible rotation - only works when using half steps (8), needs at least 2 when working with full steps (4)

**degrees**: rotation in degrees (doubles when using only full steps)

**direction**: cw for clockwise, ccw for counter clockwise

**step_start**: only required for multiple high-precision rotations
