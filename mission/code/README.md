## Mission code directory

This folder is intended for all code that is specific to the Morpion mission:

- data collection / teleoperation scripts,  
- imitation‑learning training code,  
- model definition and loading,  
- any small utilities used only for this project.  

You can organize it for example as:

- `train_imitation.py` – train the manipulation policy,  
- `policy.py` – load and run the trained model,  
- `config/` – hyperparameters, board / robot settings, etc.  

The main entry point that is used by `scripts/play_morpion.py`
should live here (or at least be imported from here).


