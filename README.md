# README
Open data for reproduction purposes of the experiments exposed in our master's thesis: "Reducing train delays in a real time context: A Constraint Programming Approach using Conditional-Time Interval variables".

A simpler model and data can be found on [CAP_RESCH_17] and the BitBucket of Quentin Cappart ([link](https://bitbucket.org/qcappart/qcappart_opendata)).

## Data available

### Ottignies-Wavre
This folder contains the data related to the traffic rescheduling problem.
Information presented here are sufficient to build the model explained in the thesis and to replay the experiments.
Files are detailed below:

* **stn**\_layout.txt: representation of the track layout of station **stn** (text).
* **stn**\_layout.pdf: track layout of station **stn** (figure).
* **stn**\_instance_homo\_**x**\_**h**\_**n**.json: instance n°**n** for an homogeneous traffic of **x** trains based on station **stn** with an horizon of **h** minutes.
* **stn**\_instance_homo\_**x**\_**h**\_**n**.bmk: benchmark about the related instance obtained with the model exposed in the thesis.

## Resources

Florian Felten and Jérôme Thiry. Reducing train delays in a real time context: A Constraint Programming Approach using Conditional-Time Interval variables, 2018.

[CAP_RESCH_17] Quentin Cappart and Pierre Schaus. Rescheduling Railway Traffic on Real Time Situations using Time-Interval Variables, 2016.
## Contact

florian.felten@student.uclouvain.be
jerome.thiry@student.uclouvain.be
