# lsmsm_project

Large-Scale Models and Simulation Methods - Agent-based Transport Simulation in Calvados, France

Report available at:\
https://luckerma.github.io/lsmsm_project/

## Setup and Run

### Installation (Conda)

```bash
conda env create -f environment.yml -n lsmsm
```

### Run (Jupyter)

```bash
conda activate lsmsm
```

Run `project.ipynb` in Jupyter.

## Report (Quarto)

### Preview Report (HTML)

```bash
quarto preview ./report/
```

### Render Report (PDF)

```bash
quarto render ./report/ --to pdf
```

### Render Report (IEEE PDF)

```bash
cd report/
quarto add dfolio/quarto-ieee
quarto render . --to ieee-pdf
```
