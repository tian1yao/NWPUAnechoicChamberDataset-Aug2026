## NWPU Anechoic Chamber Dataset (August 2026)

### Overview

This repository provides experimental acoustic array data collected in August 2026 at the anechoic chamber of Northwestern Polytechnical University (NWPU). The dataset was acquired for research on acoustic array signal processing, high-resolution direction-of-arrival (DOA) estimation, and sparse reconstruction methods.

### Experimental Environment

The experiments were conducted in the anechoic chamber at Northwestern Polytechnical University. The chamber dimensions are 11.8 m × 4.2 m × 3.8 m (length × width × height).

The microphone array and acoustic sources were placed at approximately the same elevation, with a source-to-array distance of approximately 10 m.

### Experimental Equipment

A 16-element omnidirectional microphone uniform linear array (ULA) was employed for acoustic signal acquisition. The inter-element spacing was 0.0425 m, and the sampling frequency was set to 48 kHz.

Two loudspeakers were used as acoustic sources. During the experiment, the two loudspeakers simultaneously transmitted narrowband single-tone signals at a frequency of 4 kHz for 6 seconds.

Photographs of the experimental apparatus are provided in the Experimental Apparatus Images folder of this repository.

### Dataset Description

The two acoustic sources were placed at 0° and 5° relative to the array reference direction, respectively, resulting in an angular separation of 5°. This closely spaced-source configuration was designed to evaluate the high-resolution DOA estimation performance of different algorithms.

The repository contains the experimental microphone array measurement data collected under this configuration.

The MATLAB data file contains the recorded array measurements with dimensions of **N × 16**, where:

- each column corresponds to one microphone element;
- each row corresponds to one sampled time point;
- the sampling frequency is 48 kHz;
- the recording duration is 6 seconds.

### File Format

The experimental data are provided in MATLAB `.mat` format for convenient use in acoustic signal processing, array processing, and DOA estimation research.

### Citation

If you use this dataset in your research, publications, or analyses, please cite the relevant paper:

> [Paper citation to be added after publication.]
