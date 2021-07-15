# Formal-analysis-method-of-protocol-guessing-attack

## Input-file

The input file of Tamarin is named as \*.spthy.
All example protocol models are found in the directory Input

## Analysis results

Tamarin's automated proof process is stored in directory Proof.

The protocol attack path that violates the security attribute is exported as SVG format image and stored in Trace directory.

## Usage

Automatic proof using command line mode:
~~~~
    tamarin-prover inputfile --prove --diff
~~~~
Semi automatic proof using interactive mode:
~~~~
    tamarin-prover interactive inputfile --diff
~~~~
