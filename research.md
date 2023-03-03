---
layout: page
title: Research
---

<font size="5">
Our goal is to study and better understand what happens after a molecule
absorbs a photon, particularly where a molecule may then undergo internal
conversion between electronic states.
<br/>
A more complete picture of
photochemistry gives us the ability to predict reaction products and trends
in photochemical reactions, with potential applications in light harvesting,
molecular machines and organic synthesis.
</font>


---

### Photochemical reaction pathways and conical intersection seams

![Reaction pathway passing through a conical intersecion on a seam](/images/conical_seam.svg)
{: style="float: right; margin: 1em 2em"}

Molecular dynamics are governed by potential energy surfaces, which describe
the energies of electronic states of a molecule for all changes in the
positions of atomic nuclei. Two electronic states can meet at a conical
intersection seam, which acts like a funnel that takes a molecular wavefunction
between electronic states without emitting a photon.

Much of photochemistry
involves *downhill* reactions from an excited electronic state back to the
ground state, meaning the molecular wavefunction has enough initial energy
to access many regions of the intersection seam. This is strong contrast with
the *uphill* picture used in transition state theory for thermal reactions,
and it requires a new interpretation to understand and predict photochemical
reaction outcomes.


---

### Analog quantum simulation of photochemical dynamics

![A small organic molecule being mapped onto an analog quantum computer](/images/analog_sim.svg)
{: style="float: right; margin: 1em 2em"}

Quantum mechanical systems are difficult to simulate with conventional
(classical) computers because the amount of information required to describe
a quantum state scales exponentially with the system size. Photochemical
reactions are especially difficult because they require a quantum mechanical
treatment of atomic nuclei in addition to the electrons.

Quantum computing show promise as a platform for quantum chemical calculations
at a lower computational cost; however, early *digital* quantum computers
composed of quantum bits (qubits) are limited in
size and number of operations due to environmental noise. In contrast,
an *analog* quantum computer uses a controllable quantum system in a laboratory
to simulate a system of interest, such as a molecule. With a suitable analog
of a photoexcited molecule, a simulation consists of creating a desired initial
state, then letting it evolve naturally with time and performing measurements.


---

### Digital quantum simulation of photochemical properties

![A hydrogen transfer reaction being mapped onto a digital quantum computer](/images/digital_sim.svg)
{: style="float: right; margin: 1em 2em"}

The last decade has shown great advances and ever-increasing interest in
the development of quantum computers. One of the earliest foreseeable benefits
of quantum computers is for the simulation of quantum mechanical systems,
including quantum chemistry.

Most quantum chemistry methods, including those developed for future quantum
computers, involve the Born-Oppenheimer approximation. It separates the
equations for electrons and nuclei such that electrons behave as though the
nuclei are fixed in place. This approximation has resulted in many efficient
algorithms for the simulation of properties with classical computers, but it
breaks down during photochemical dynamics involving internal conversion.
Digital quantum computers give us the opportunity to re-think quantum chemistry
methods with a more complete quantum mechanical description, with greater
accuracy for nuclear quantum effects in photochemistry.
