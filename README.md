## Handstand

Handstand is a set of pybullet/pyrosim-based functions for evolving a robot from random that is optimized to hold a handstand. The fitness function maximizes the distance between the average z-position of the back feet and the average z-position of the front feet.

The design for the robot's body is based on dwarf mongooses, one of nature's best handstand-ers:

![mongoose](https://www.zoochat.com/community/media/dwarf-mongoose-gymnastics.304530/full?d=1440614611)


## Usage

Please make sure all of the attending files from this repository are present in your working directory (e.g., by cloning this repo to your local system).

Run the following in the command line:

```bash
python3 searchHandstand.py
```


## Output

The pre-set constants run the evolution algorithm for 100 generations of 1 parent producing 1 child. This value can be changed in ```constants.py``` to alter the population size or number of generations. 

A parent will be replaced with its child if its child's fitness value exceeds its own. The first randomly generated and final optimized parent will be displayed in the simulation interface. Intervening generations will not be shown, but the terminal will display the fitness values of the current parent and child.


## Citations
Bongard, J. [u/DrJosh]. “Education in Evolutionary Robotics” Reddit, 6 Feb. 2023, https://www.reddit.com/r/ludobots/.

Kriegman, S. Artificial Life, Northwestern University, Evanston, Illinois, Winter 2023. 
