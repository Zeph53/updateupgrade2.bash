This is a BASH script that allows users to run various update and upgrade commands automatically and 
without a lot of human interaction, or notification about warnings or incompatibilities. 
Best used in an enterprise environment, with a proprietary list of repositories, or those on a rolling repository.

There is a chance that DPKG will create a lock-up issue with APT, without telling you, in such case it is safe to assume that your PC is now broken and there is nothing I can think of right now to fix it. 

Run "/bin/bash dpkg --configure -a"
