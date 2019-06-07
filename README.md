# mentorship-notebooks

This repository contains the source code that I developed during my time at MITRE in spring 2019. (Later, I might add Steven's code as well.) This collects all the code in a single, easy-to-share location.

## Contents

This is a high-level description of the files contained herein:

### Meta Stuff

These files contain information about the repository itself or the source code within.

* `README.md`: this document
* `Summary_of_Results.ipynb`: a copy of the final project report
* `IBM_Backend_Usage.ipynb`: a brief self-reference for using Qiskit
* `Scrapbook.ipynb`: some scrap calculations

### Project Code

These notebooks contain the programs/experiments run for this project. They should be reproducible, although you will need IBM Q credentials and may need to tweak some things.

* `Basic_Error_Rate.ipynb`: state initialization and measurement errors
* `Energy_Relaxation_Measurement`: an early T1 test, largely superseded by later ones/Steven's work
* `Ignis_T1_Tests.ipynb`: a single-qubit T1 test using the Qiskit Ignis framework's circuit generator and analysis tools
* `Ignis_T2_Tests.ipynb`: T2 tests using Qiskit Ignis; note that this is **not** the actual Ramsey decoherence (which Ignis terms T2*)
* `T1_Variations.ipynb`: an attempt to measure relative T1 values between qubits; this has largely been superseded
* `T1_Variations_Sketchy_Business_Investigation.ipynb`: documents the investigation into the strange errors that occurred when measuring multiple T1s at once; identified cause as Qiskit's auto-optimization
* `T2star_Variations.ipynb`: final experiments to measure T2 (Ramsey decoherence)
* `Two_Qubit_Gates.ipynb`: experiments to characterize performance of multi-qubit gates
* `img/`: various images to be put in documents; neither thorough nor complete, and not that important

### Other Miscellany

These files were generated during our "playing around/familiarizing ourselves" with Qiskit time. They don't include anything of note in terms of the actual project, but they are included here for the sake of thoroughness in documenting my work at mentorship.

* `Quantum_Error_Correction.ipynb`: an implementation of the three-qubit error correction code described by Dr. Rodenburg in his lectures
* `Quantum_RNG.ipynb`: an attempt to implement a verifiable quantum random number generator that I read about in a paper; the attempt failed with some interesting statistical results
* `Quantum_Teleportation.ipynb`: an implementation of a rudimentary quantum teleportation protocol

