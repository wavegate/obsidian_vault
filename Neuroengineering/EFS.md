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

## What is a salt bridge?
# What happens at the cell membrane?
- Effects of an electric field on neuronal tissue are caused by an establishment of a transmembrane potential
- When a neuron is positioned inside an electric field, the electric field will induce a change in the resting transmembrane potential by superimposing an electrically-induced transmembrane potential (TIP)
- Under extreme conditions, a large induced potential can generate a configuration change in the membrane, forming pores and causing electroporation
- the properties of the externally-applied electric field play significant roles in membrane polarization; these include direction, intensity, frequency,and waveform of the field.

## What is an electrically-induced transmembrane potential?

# What is the structure of the DRG organ?
bulge in posterior spinal root, located bilaterally in the intraforaminal space at each spinal vertebral level
contains cell bodies of all primary sensory neurons innervating that dermatome governed by spinal segmental level

beginning of all somatosensory pathways except for those in the head

responsible for thermoception (sensing temperature), nociception (feeling pain), mechanoreception (sensing pressure) and proprioception (sensing body spatial position)

peripheral DRG branch has axonal hallmarks
- site of axon potential generation
- uniform diameter
- myelinated in some cases
- positive for the somatodendritic marker microtublue-associated protein 2 (MAP2) raising the hypothesis that at the molecular level it has some dendritic-like features

![[Pasted image 20210725225713.png]]

- a lot of heterogeneity
- originate from neural crest (in contrast t oneural tube like CNS)
- migrate ventrally to the DRG between E8.5 and E10 in the mouse
- specified from cell progeny of neural crest cells in two overlapping successive waves controlled by neurogenin 1 and 2

supported by two types of glial cells: satellite glial cells (SGCs) and Schwann cells
- SGCs interact with the cell bodies and initial part of the stem axon
- Schwann cells envelop distal part of stem axon adn both peripheral and central axons


![[Pasted image 20210725231028.png]]

- cell bodies are completely wrapped by sheaths that may have one or sveeral layers of SGCs

![[Pasted image 20210725231226.png]]

- stem axon can be very long
- proximal region of stem axon is always unmyelinated 
- distal part of stem axon is ensheathed by Schwann cells and can be myelinated
- 
# How is the calcium signalled?
- Ca2+ channels are present throughout the different parts of the neuron (dendrites, soma, synaptic terminals)
- Ca2+ currents can be separated into transient, long lasting, and neither
- At physiologic membrane potential, VGCCs are normally closed
- The concentration of calcium is normally several thousand times higher outside the cell than inside
- Based on similar structural elemenets, the voltage-gated NaV, CaV, and KV channels are classified as the S4 channel superfamily. In this family, the voltage sensor consists of several positively charged residues in the fourth TM segment.
- Neurons were stimulated in imaging buffer containing a drug cocktail to inhibit synaptic receptors (10 mM CNQX, 10 mM(R)-CPP, 10 mM gabazine, 1mM (S)-MCPG, Tocris Bioscience). Under these conditions, intracellular calcium increases are presumably caused by the opening of voltage sensitive calcium channels.
- Neurons have unusually fast calcium dynamics and low peak calcium accumulation
- GCaMP consist of circularly permuted green fluorescent protein, the calcium-binding protein calmodulatin (CaM) and CaM-interacting M13 peptide
- Calcium-dependent conformational changes in CaM-M13 cause increased brightness with calcium binding

![[Pasted image 20210727143354.png]]

![[Pasted image 20210727145429.png]]

# How does the calcium signal travel to the camera?
- The specimen is illuminated with light of a specific wavelength which is absorbed by fluorophores, causing them to emit light of longer wavelengths
- The illumination light is separated from the much weaker emitted fluorescence through the use of a spectral emission filter
- 