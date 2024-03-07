# BCI_Project

## Project description
This project is about applying **Artificial Intelligence** and **Deep Learning** in **Brain-Computer Interfacing** for Health-care Issues.

## Project Technology Keywords
- Python
- Deep learning (CNN, LSTM, and Transformer)
- Data Acquisition and Analytics
- BCI
- Neuroscience

## Project Deliverables:
- [x]  Data Acquisition
- [x]  Preprocessing Data (eye-closed *EC* /eye-open *EO*  resting state data) 
- [ ]  Classification Model Architecture Design
- [ ]  Model Implementation
- [ ]  Model Training
- [ ]  Model Evaluation
- [ ]  GUI (optional)

## Project Structrue
- *data* folder: EEG Dataset
- *src* folder: source code

## Development Kernel(environment) needs
- numpy
- h5py
- matplotlib
- mne
- plotly.express
- pandas

## Devlopment Setup Instructions
  1. Clcik the <> Code Green button, in **Local**, Copy the Clone URL ```https://github.com/LilVegedog/BCI_Project.git```
  2. In your computer, Choose one folder, right click it, find "Git Bash Here" and click it. Then a terminal window would pop up.
  3. In the terminal, type:
     ``` git clone https://github.com/LilVegedog/BCI_Project.git```
     and return(click "enter" key). The the result should show like this:
     ``` Cloning into 'BCI_Project'...\
        remote: Enumerating objects: 41, done.\
        remote: Counting objects: 100% (41/41), done.\
        remote: Compressing objects: 100% (33/33), done.\
        remote: Total 41 (delta 11), reused 32 (delta 5), pack-reused 0\
        Receiving objects: 100% (41/41), 27.78 MiB | 24.35 MiB/s, done.\
        Resolving deltas: 100% (11/11), done.```
  4. In the terminal, type  ``` ls ``` to check whether there is a folder BCI_Project/ exist.
  5. type ``` code .``` and the Visual Studio Code will automatically pop up the window and open the BCI_Project Folder.
     
> [!NOTE]  
> MNE-Python requires Python version 3.8 or higher, if you need help installing Python, please refer to the [Install Python](https://pip.pypa.io/en/stable/installation/)

6. (If your current python environment have: mne,numpy,matplotlib,plotly,pandas, then you can skip this.)
     - ```ctrl + ` ``` open the terminal.
     - type ```pip install mne ``` and return
     - type ```pip install numpy ``` and return
     - type ```pip install h5py ``` and return
     - type ```pip install matplotlib ``` and return
     - type ```pip install plotly ``` and return
     - type ```pip install pandas ``` and return
## EEG Data Pre-processing Mind Mapping
![BCI EEG Data Pre-processing](https://github.com/LilVegedog/BCI_Project/assets/99380263/ab190b72-2dd1-4f11-b24d-2f0e79e3fce5)
