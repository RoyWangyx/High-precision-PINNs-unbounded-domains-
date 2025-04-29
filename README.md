#readme

LBFGS.py: modified LBFGS
modified*: SS-Broyden optimizers, from https://github.com/jorgeurban/self_scaled_algorithms_pinns

Files of the 2D Boussinesq example
bous_final.ipynb: main file
*9999final.pth: profiles after 10000 iterations of Adam
*40000final.pth: profiles after 10000 iterations of Adam followed by 40000 iterations of SS-Broyden
results.pkl: losses of Adam
losses.pkl: losses of SS-Broyden

Files of the Burgers example:
cutoffbur(04).ipynb: main file using exact asymptotics for lambda=0.5(0.4)
weak_asymp_bur(04).ipynb: main file using weak asymptotics for lambda=0.5(0.4)
