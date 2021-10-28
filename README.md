# audio-dsp-example
Simple example how to do some audio processing in Python. 

This example calculates RMS within short-time windows of a wave file and uses this parameter to control a low-pass filter cutoff frequency.

## setup

#### conda
* Install conda environment with `conda env create -f dev_env_conda.yml`.
* activate environment with `conda activate audio-dsp-example`
* run `jupyter notebook` and open `main.ipynb` in your browser

#### nix
* install [nix](https://nixos.org/)
* just run `nix-shell`
