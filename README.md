# Readme file: Mini-Project

- [Aim of the project](#aim-of-the-project)
- [Description of the project](#description-of-the-project)
- [Folders](#folders)

        [Jupyter_notebooks](#jupyter_notebooks)
    
        [Matflow_workflows](#matflow_workflow)
- [Prerequisites](#prerequisites)
- [Usage](#usage)


## Aim of the project: 
Study the effect of texture on the stress and strain localisation duringaluminium sheets bending.

## Description of the project:
Premature failure can occur at the grain boundaries on the top surface of aluminium sheets duringbending. Materials with different textures have different bendability, but the origin of this correla-tion is not known. In this project, crystal plasticity modelling was used to study the relationshipbetween stress and strain localisation and texture in three alloys with different textures. The VonMises stresses, effective strain and triaxiality values were extracted from uniaxial and plane straintension simulations to a target strain of 15 %. As expected, damage indicators like triaxiality andstrain localisation were higher for the plane strain than for the uniaxial simulations. However,no clear relationship between texture and damage indicators could be found. In future work, thismodel will be improved to represent the grain shapes and grain boundary misorientations morefaithfully, so that more realistic predictions of stress and strain localisation can be made.

## Folders:

- **Jupyter_notebooks** --> This folder has the Jupyter notebooks used to plot the results in different types of graphs.

- **Matflow_workflows** -->  This folder has the .yml files used to run the simulations.
    
         
## Prerequisites:

It is necessary to install the following packages to run the code.

* matplotlib 3.4.2
  ```sh
  pip install matplotlib
  ```
* numpy 1.20.3
  ```sh
  pip install numpy
  ```
* install matflow
  ```sh
  pip install matflow
  ```
* update matflow
  ```sh
  pip install -U matflow 
  ```
* install version of matflow
  ```sh
  pip install matflow==0.2.15
  ```
  

## Usage:
 
1. Install the Python packages described in the prerequisites section of this README file.
2. Download the code from:
   ```sh
   https://github.com/lauragondu/Mini-project.git
   ```
3. Open the demo notebooks to see the results and the code used to obtain them.

