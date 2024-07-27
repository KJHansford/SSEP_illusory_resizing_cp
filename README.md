These materials are a computationally reproducible version of the paper:

Hansford, K.J., Baker, D.H., McKenzie, K.J. & Preston, C.E.J. (2024). Somatosensory Response Changes During Illusory Finger Stretching in Participants with Chronic Hand-Based Pain.

The file manuscript.qmd is an Quarto file that will perform all analyses and figure creation, and produce a pdf version of the manuscript. You can set 'processdata' to 0 which will create the manuscript using preprocessed EEG data, or you can set 'processdata' to 1 which downloads raw EEG data from OSF and runs all the processing - this cannot be run using github actions due to storage constraints, so you would need to create a local copy of the material to create the manscript from the raw data.

The full repository can be downloaded (cloned), and contains all the required data files. However if any data files are missing the code will attempt to download them from the OSF repository for this project: (https://osf.io/dzmf9/)
