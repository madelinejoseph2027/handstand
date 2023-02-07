## Handstand

Handstand is a set of pybullet/pyrosim-based functions for evolving a robot from random that is optimized to hold a handstand.
The design for the robot's body is loosely based on dwarf mongooses:

![mongoose](https://www.zoochat.com/community/media/dwarf-mongoose-gymnastics.304530/full?d=1440614611)

## Output

The pre-set constants run the evolution algorithm for 100 generations of 1 parent producing 1 child. This value can be changed in ```constants.py``` to alter the population size or number of generations. The first randomly generated and final optimized parent will be displayed in the simulation interface.

## Usage

Run the following in the command line:

```bash
python3 searchHandstand.py
```

Please make sure all of the attending files from this repository are present in your working directory. 

## Citations
Bongard, J. [u/DrJosh]. “Education in Evolutionary Robotics” Reddit, 6 Feb. 2023, https://www.reddit.com/r/ludobots/.

Kriegman, S. Artificial Life, Northwestern University, Evanston, Illinois, Winter 2023. 
