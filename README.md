**Final solution** for [Predicting Molecular Properties](https://www.kaggle.com/c/champs-scalar-coupling) competition **placed 372nd** from 2749 competitors and teams.

# About Predicting-Molecular-Properties-Kaggle-competition-

This challenge aims to predict interactions between atoms. Imaging technologies like MRI enable us to see and understand the molecular composition of tissues. Nuclear Magnetic Resonance (NMR) is a closely related technology which uses the same principles to understand the structure and dynamics of proteins and molecules.

Researchers around the world conduct NMR experiments to further understanding of the structure and dynamics of molecules, across areas like environmental science, pharmaceutical science, and materials science.

This competition is hosted by members of the CHemistry and Mathematics in Phase Space (CHAMPS) at the University of Bristol, Cardiff University, Imperial College and the University of Leeds. Winning teams will have an opportunity to partner with this multi-university research program on an academic publication

## About Scalar Coupling

Using NMR to gain insight into a molecule’s structure and dynamics depends on the ability to accurately predict so-called “scalar couplings”. These are effectively the magnetic interactions between a pair of atoms. The strength of this magnetic interaction depends on intervening electrons and chemical bonds that make up a molecule’s three-dimensional structure.

Using state-of-the-art methods from quantum mechanics, it is possible to accurately calculate scalar coupling constants given only a 3D molecular structure as input. However, these quantum mechanics calculations are extremely expensive (days or weeks per molecule), and therefore have limited applicability in day-to-day workflows.

A fast and reliable method to predict these interactions will allow medicinal chemists to gain structural insights faster and cheaper, enabling scientists to understand how the 3D chemical structure of a molecule affects its properties and behavior.

Ultimately, such tools will enable researchers to make progress in a range of important problems, like designing molecules to carry out specific cellular tasks, or designing better drug molecules to fight disease.

## The solution
The solution I worked for in the last couple of months wasn't anything expectacular or novel, hence my place in the lederboard. This was my first competition, from which i learned a great deal. 

My best individual model was a LGBM model with hyperparameters discovered with bayesian optimization and a set of all the best features I found in the public kernels, and some of my own. That gave me a score of -1.572. The final submision was a blend of my model and the best public models of the competitions, scoring a -1.869 in the private leaderboard and -1.875 in the public leaderboard.  

## How to use this repository

Download competition data from this [link](https://www.kaggle.com/c/champs-scalar-coupling/data) and place it in the champs-scalar-coupling folder. 

The external data used was a mix of all the features created in public kernels that I thought interesting to add to my model. This can be found [here](https://drive.google.com/drive/folders/1p4hcH7mPcyT4nho0wPrlpObTb_VUkgDD?usp=sharing) Download it and place it in the External data folder. 

Now you can run the final model notebook. **Important** the data used for this competition is very large and needs at least 16gb of ram capacity.
