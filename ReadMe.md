### QRAT - A Reachability Analysis Tool for Quantum Programs
---
This repository presents QRAT - a reachability analysis tool for quantum programs, which was developed in Maude.

## Dependencies
- Maude is a programming/specification language based on rewriting logic. How to download and install Maude can be found [here](http://maude.cs.illinois.edu/w/index.php/The_Maude_System).
- An algebraic specification for quantum computation ([|AS4QC>](https://github.com/canhminhdo/ket-as4qc)) as a submodule in this repository.

## How to install
- Clone the source code to your computer and go to the source code directory.
```console
git clone --recurse-submodules https://github.com/canhminhdo/qrat.git && cd qrat
```

- Feed a Maude file that is the formal specification of quantum programs being verified into Maude.

For example, we can type the following command in CLI in order to conduct rechability analysis for Quantum Teleportation Protocol specified in the `teleport.maude` file:

```console
maude teleport.maude
```

- For testing, go to the `test` folder and run the `./tester` file in CLI.

## Case Studies
We successfully verify the correctness of some quantum programs with reachability analysis:
- Quantum Teleportation Protocol
- ...

## Publication
- TBA
