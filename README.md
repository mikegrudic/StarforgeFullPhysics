# StarforgeFullPhysics
Repository containing files and links to material associated with Grudic et al. 2022 STARFORGE full feedback physics paper. This repository may be updated over time in response to community feedback.

If you found this data useful for your study please cite the paper: https://arxiv.org/abs/2201.00882

# [Sink Particle Data](http://www.starforge.space/data/stars_M2e4_fullphysics.tar.gz)

Contains all raw sink particle data from the simulation in the paper, in the form of standard GIZMO hdf5 snapshots but with gas data removed. 

Unless otherwise specified, the system of units adopted for these data is as follows:

Mass: 1 solar mass

Length: 1 parsec

Speed: 1 m/s

Magnetic field: 1 Tesla

Hence e.g. your unit of time would be 1 parsec / 1m/s ~ 1 Gyr

General documentation on the formatt of GIZMO snapshots is available here: http://www.tapir.caltech.edu/~phopkins/Site/GIZMO_files/gizmo_documentation.html

**PartType5/BH_AccretionLength**: Radius within which gas cells are considered for accretion and local feedback injection.

**PartType5/BH_Mass**: Mass of the actual star or protostar that lives in the sink.

**PartType5/BH_Mass_AlphaDisk**: Mass of the accretion reservoir contained within the sink (note: this does not represent a physical disk mass!)

**PartType5/BH_Mdot**: Stellar accretion rate: units are 1 solar mass * (1m/s) / (1pc) ~ solar mass Gyr^-1

**PartType5/BH_NProgs**: Not used in STARFORGE simulations.

**PartType5/BH_Specific_AngMom**: Specific angular momentum of the star (total angular momentum / stellar mass)

**PartType5/Coordinates**: Coordinates of the sink particle.

**PartType5/Mass_D**: Total deuterium mass in the star.

**PartType5/Masses**: Total mass of the sink (accretion reservoir + stellar mass)

**PartType5/Metallicity**: Metal and feedback tracer mass fractions (see GIZMO documentation for details)

**PartType5/ParticleChildIDsNumber**: Not used in STARFORGE simulations.

**PartType5/ParticleIDGenerationNumber**: Not used in STARFORGE simulations.

**PartType5/ParticleIDs**: Unique particle ID

**PartType5/Potential**: Gravitational potential, counting contributions of all other stars and gas.

**PartType5/ProtoStellarAge**: Time at which the sink particle originally formed.

**PartType5/ProtoStellarRadius_inSolar**: Stellar radius in solar radii

**PartType5/ProtoStellarStage**: Evolutionary stage of the star, following Offner 2009: 0 - precollapse, 1 - no burning, 2 - core D burning at fixed Tc, 3 - core D burning at variable Tc, 4 - shell D burning, 5 - main sequence, 6 - going supernova

**PartType5/SinkRadius**: Maximum radius for a gas cell to be accreted.

**PartType5/StarLuminosity_Solar**: Bolometric luminosity in solar luminosities

**PartType5/StellarFormationTime** : Time at which the star last advanced in evolutionary stage.

**PartType5/Velocities**: Velocity

**PartType5/ZAMS_Mass**: The greatest mass that the star ever attained while on the main sequence.
