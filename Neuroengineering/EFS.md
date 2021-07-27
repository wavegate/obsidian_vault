# What is a pulse stimulator?
Grass SD9 Square Pulse Stimulator
![[Pasted image 20210727103141.png]]
- Designed for student teaching
- Built-in isolation providing higher level of safety
- Voltage device only, does not generate constant current
- Generates pulses from 20 microseconds to 200 milliseconds in duration, with interpulse frequencies from 0.2 Hz to 200 Hz
- Output voltage could be defined from 100 mV to 100 V
- No software control
- 100V Monophasic, no biphasic
- Requires optional SIUs for current control
- No control over train duration/frequency

## What is electrical isolation?
## What is a square wave?
## What is a monophasic?
# What is an oscilloscope?
- Measures voltage between scope ground and tip of probe
- Travels through coaxial cable to a BNC connector
- Tip of probe can be a hook that grabs to wires or can remove it to probe different parts of circuit
- Plots voltage change over time 
- Can adjust x (time) and y (voltage) scales using knobs
- Scope ground is connected to earth through power cord which is eventually shorted to the neutral. If I accidentally connected the scope ground to the live wire I short the power lines. Can use adapter to bypass the earth ground.
- Need electrical circuit basic understanding to continue
# What does electrical stimulation do to the bath?
- Bath is artificial CSF: 124 mM NaCl, 5 mM KCl, 20 mM HEPES, 10 mM D-glucose, 1.3 mM MgCl2, 1.5 mM CaCl2, 26 mM NaHCO3, 1.25 mM NaH2PO4
- Electrically conducting solution when dissolved in a polar solvent (water)
- Cations and anions dissolve uniformly through the solvent (solvation)
- If an electrical potential is applied to the solution, the cations are drawn to the electrode with abundance of electrons, and the anions are drawn to the electrode with a deficit of electrons
- When electrodes are placed in an electrolyte and a voltage is applied, the electrolyte will conduct electricity
- A chemical reaction occurs at the cathode, providing electrons to the electrolyte
- Another reaction occurs at the anode, consuming electrons from the electrolyte
- As a result, a negative charge cloud develops in the electrolyte around the cathode, and a positive charge develops around the anode
- The ions in the electrolyte neutralize these charges, enabling the electrons to keep flowing and the reactions to continue
- This movement of anions and cations amounts to a current
- When a stimulus is applied to a physiological medium, a redistribution of charge first occurs, and then, if the stimulus is of long-enough duration, the electrodes will begin to chemically react with the medium to sustain current.
- A system delivering short stimulation pulses can thus be designed to allow only a tolerable amount of chemical reactions to occur by selecting the electrode properties and pulse characteristics that favor reversible redistributions of charge in the double layer at the electrode–electrolyte interface and reversible chemical reactions32
- We have found that a square-wave pulse with relatively short-duration (2 ms, or 0.2% of the total cycle) and a relatively long time between pulses, with the carbon electrodes used throughout this protocol, provides time for the vast majority (B85%) of the processes occurring between electrodes and the electrolyte to reverse28.
- In addition, experimentally, we have also identified a safe stimulation range using carbon rod electrodes with neonatal rat cardiomyocytes, and at this point, we do not recommend stimulation at levels of 8 V/cm and above, although we may refine this range in the future28.
- A system delivering DC stimuli (such as that shown in Box 1 using Ag/AgCl electrodes which efficiently corrode, providing a steady current) is different than one delivering short pulses, as it necessarily generates chemical byproducts and therefore must be designed to shield the cells from chemical reactions by the use of salt bridges
- As the incorporation of salt bridges necessarily adds another level of complexity, these systems are recommended only if the signal of interest generates intolerable amounts of chemical reactions.
- The injection of charge from the electrode into electrolyte (culture medium in our case) can be accomplished by either attaching a current source between the two electrodes (that defines the current to be passed) or applying a voltage source.
- Although the second method is simpler to implement, it enables only the control of the net potential between the two electrodes, and not of the current, which, rather than voltage, dictates the amount of electrical field applied to the cells
- Nonetheless, for pulsatile electrical field stimuli delivered by carbon electrodes, we have found that a voltage-controlled source is sufficient for accomplishing stimulation (for the DC stimulation applied in Box 1, however, a current controlled device is utilized).

![[Pasted image 20210727134649.png]]

- The well-defined chamber geometry permits application of a prescribed electrical field strength or current density. Two salt bridges prevent electrolysis products from contaminating the chamber by providing a pathway for current from each media reservoir to an Ag–AgCl electrode (one positive: anode, and one negative: cathode). Salt bridges are prepared from flexible plastic tubing filled with 2% agarose in PBS. This chamber is ideally suited for DC stimulation because of its well-defined geometry. However, to attain voltages in the physiological range, high voltage levels are needed to overcome high electrical resistance of system. In addition, because of corrosion of the silver/silver chloride electrodes, the electrical resistance of the system is constantly changing, necessitating a current-controlled system. We recommend the Keithley SourceMeter 2410.

![[Pasted image 20210727122622.png]]

- For example, for NaCl in water, the cathode reaction will be 2 H2O + 2e− → 2 OH− + H2, and the anode reaction will be 2 NaCl → 2 Na+ + Cl2 + 2e−
- This means hydrogen gas will bubble up and chlorine gas will be liberated into solution where it reacts with sodium and hydroxyl ions to produce sodium hypochlorite - household bleach
- How well the current passes depends on how much ion is dissolved
- Can measure conductance in units of siemen (S) with conductivity probe
- We should be able to change the "current" or ion flow rate through the liquid by increasing concentration of the salts

# What is a salt bridge?

# What is the structure of the DRG organ?
# What happens at the cell membrane?
- Effects of an electric field on neuronal tissue are cauesd by an establishment of a transmembrane potential
- When a neuron is positioned inside an electric field, the electric field will induce a change in the resting transmembrane potential by superimposing an electrically-induced transmembrane potential (TIP)
- Under extreme conditions, a large induced potential can generate a configuration change in the membrane, forming pores and causing electroporation
- Neurons are activated by electrolyte activity between the extracellular fluid and intracellular fluid
- Electrolytes enter or leave the cell membrane through ion channels
# How is the calcium signalled?

GCaMP6s signaling
# How does the calcium signal travel to the camera?
Fluorescence microscopy