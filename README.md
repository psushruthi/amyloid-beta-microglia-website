# Measuring how brain immune cells clear Alzheimer's protein

**Live project website:** https://psushruthi.github.io/amyloid-beta-microglia-website/

This repository holds the public project website for an automated image analysis pipeline built for Alzheimer's disease drug research.

## About the project

Researchers are testing whether a potential Alzheimer's drug helps the brain's immune cells (microglia) clear a harmful protein (amyloid-beta). Answering that question means measuring hundreds of microscope images. Doing that manually is slow, and results can vary between people and sessions.

The pipeline solves this by measuring every image the same way, automatically. For each image it reports:

- **Uptake:** the percent of immune cell area that contains the protein
- **Cell count:** the number of cell nuclei in the image
- **Check images:** a picture for every number, so results can be reviewed by eye
- **Traceability:** a results table with the settings saved in every row, a run log and a visual report

Anyone on the team can run it without writing code.

## Skills and tools

- **Image analysis:** Fiji / ImageJ, thresholding, object counting, colocalization analysis, batch image processing
- **Programming:** Python (Jython), ImageJ API, automated reporting, HTML and CSS
- **Data and documentation:** data standardization, CSV data design, audit trail, Git and GitHub, technical writing, GitHub Pages

## Pipeline code

The pipeline code and full documentation are kept in a separate repository:
[psushruthi/amyloid-beta-microglia](https://github.com/psushruthi/amyloid-beta-microglia)

That repository is **private** because the work has not been published yet. To request access, email spanakan@iu.edu.

## What's in this repository

```
index.html     the project website
assets/        one sample image set (three channels) shown in the interactive viewer
```

## Credits

- **Pipeline development and documentation:** Sushruthi Panakanti, BDS, MSHI, Research Data Analyst, Oblak Lab
- **Experimental design, experiments and imaging:** Claudia Rangel-Barajas, Ph.D., Assistant Research Professor and Project Manager, Oblak Lab, with support from the MODEL-AD Lab team

Stark Neurosciences Research Institute, Indiana University School of Medicine, Indianapolis, IN

## Contact

- LinkedIn: https://www.linkedin.com/in/spanakanti/
- GitHub: https://github.com/psushruthi
- Email: spanakan@iu.edu
