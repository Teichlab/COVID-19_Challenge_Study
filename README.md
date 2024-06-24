# COVID-19 Challenge Study

Repository with Rmarkdown files and Python notebooks and code to reproduce the figures from the manuscript.
- RL007_challengeStudy_PBMCs_processing.Rmd and RL007_challengeStudy_nasopharyngeal_processing.Rmd contain R code for processing the single cell data
- RL007_challengeStudy_analysesAndVisualisations.Rmd contains analyses and visualisations of the figures in the manuscript that were generated in R
- challenge_figures_LMD.ipynb contains Python code for several analyses, including most of the TCR analyses
- GPR_predict_time_since_exposure is a directory that contains code, a model, and its output, to predict time since viral exposure based on predicted cell type abundances
- A separate GitHub repo ([Cell2TCR](https://github.com/Teichlab/cell2tcr)) contains the code and a tutorial to use our Cell2TCR workflow to identify activated TCR clonotype groups

## Installation - Python environment

1. Create a new conda environment

```
conda create --name challenge_py_env python=3.9
conda activate challenge_py_env
```

2. Install packages

```bash
git clone git@github.com/teichlab/cell2tcr.git
cd cell2tcr
pip install .
```

```bash
pip install statannotations
```


3. Optional: Add kernel for use in Jupyter notebooks

```
python -m ipykernel install --user --name challenge_py_env
```

## Human SARS-CoV-2 challenge uncovers local and systemic response dynamics
[Published in Nature 19.06.2024](https://doi.org/10.1038/s41586-024-07575-x)

Rik G. H. Lindeboom*, Kaylee B. Worlock*, Lisa M. Dratva, Masahiro Yoshida, David Scobie, Helen R. Wagstaffe, Laura Richardson, Anna Wilbrey-Clark, Josephine L. Barnes, Lorenz Kretschmer, Krzysztof Polanski, Jessica Allen-Hyttinen, Puja Mehta, Dinithi Sumanaweera, Jacqueline M. Boccacino, Waradon Sungnak, Rasa Elmentaite, Ni Huang, Lira Mamanova, Rakesh Kapuge, Liam Bolt, Elena Prigmore, Ben Killingley, Mariya Kalinova, Maria Mayer, Alison Boyers, Alex Mann, Leo Swadling, Maximillian N. J. Woodall, Samuel Ellis, Claire M. Smith, Vitor H. Teixeira, Sam M. Janes, Rachel C. Chambers, Muzlifah Haniffa, Andrew Catchpole, Robert Heyderman, Mahdad Noursadeghi, Benny Chain, Andreas Mayer, Kerstin B. Meyer, Christopher Chiu, Marko Z. Nikolić† & Sarah A. Teichmann†
