# Neuromuscular-Transfemoral-Prosthesis-Model


This repository contains neuromuscular models of an amputee walking on a transfemoral prosthesis. 
The model was used to obtain the results presented in: 

Thatte, Nitish, and Hartmut Geyer. "Toward balance recovery with leg prostheses using neuromuscular model control." IEEE Transactions on Biomedical Engineering 63.5 (2016): 904-913.

To run one the model add the root folder and the Animation and Prosthesis folders to your Matlab Path.

1. Go to the folder for the model you wish to run.
2. Load one of the optimizedGains.mat files in the Results folder
3. Run assignGains.m
4. Run the model
5. Animate the result by calling animPost(animData). The animPost function has several options, check them out by opening animPost.m in the Animations folder.
