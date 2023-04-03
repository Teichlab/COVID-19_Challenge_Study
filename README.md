# COVID-19 Challenge Study

Repository with notebooks and code to reproduce the figures from the manuscript.

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

## Human SARS-CoV-2 challenge resolves local and systemic response dynamics
Rik G.H. Lindeboom*, Kaylee B. Worlock*, Lisa M. Dratva, Masahiro Yoshida, David Scobie, Helen R. Wagstaffe, Laura Richardson, Anna Wilbrey-Clark, Josephine L. Barnes, Krzysztof Polanski, Jessica Allen-Hyttinen, Puja Mehta, Dinithi Sumanaweera, Jacqueline Boccacino, Waradon Sungnak, Ni Huang, Lira Mamanova, Rakesh Kapuge, Liam Bolt, Elena Prigmore, Ben Killingley, Mariya Kalinova, Maria Mayer, Alison Boyers, Alex Mann, Vitor Teixeira, Sam M. Janes, Rachel C. Chambers, Muzlifah Haniffa, Andrew Catchpole, Robert Heyderman, Mahdad Noursadeghi, Benny Chain, Andreas Mayer, Kerstin B. Meyer, Christopher Chiu, Marko Z. Nikolić†, Sarah A. Teichmann†