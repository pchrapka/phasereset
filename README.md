phasereset
==========

phasereset is a MATLAB package that allows the generation of simulated EEG data via the classical theory and phase reset. The aim of this project is to provide a more MATLAB friendly version of the original phasereset code in the form of a separate package to avoid name collisions.

The original work and a brief tutorial can be found at http://www.cs.bris.ac.uk/~rafal/phasereset/.

setup
-----

Two options:

1. Use the bash script
    ```
    sh setup.sh
    ```
    which downloads and unzips the package into your MATLAB user folder.

2. Clone the repo
    ```
    git clone https://github.com/pchrapka/phasereset.git
    ```

usage
-----

Add the path to your MATLAB project.
```
addpath(path_to_phasereset);
```

Use the functions within your script by referencing the package functions
```
phasereset.peak()
phasereset.noise()
etc.
```