# Competency Queries Tutorials

A collection of tutorials in the form of Jupyter notebooks, detailing how to work with Competency queries in the context of SCKAN/Flatmap.

## Jupyter Notebooks Overview

* **check\_map.ipynb**
  Demo for comparing `Neuron Population` information from Map and SCKAN.

* **fma\_nerve.ipynb**
  Explore how nerve structures are represented in the **Foundational Model of Anatomy (FMA)** ontology.

* **pg\_human\_nerves.ipynb**
  Investigate the Coverage of Nerves in SCKAN/Flatmap Neuron Populations within the Human Scaffold.

* **pg\_nerves.ipynb**
  Demo for Exposing Neuron Population and Nerve-Related Information from PostgreSQL.

* **sckan\_nerves.ipynb**
  Demonstrate how to work with SCKAN nerve.

* **species\_specific.ipynb**
  Demo for retrieving species-specific neuron populations and their supporting evidence.

## Running the Tutorials

1. Create a virtual environment:

   ```bash
   python -m venv .venv
   ```

2. Activate the virtual environment:

   ```bash
   source .venv/bin/activate
   ```

3. Install required libraries:

   ```bash
   pip install -r requirements.txt
   ```

4. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open and run the desired notebook.

