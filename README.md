## Learn Quantum Computing with Python and Q#

### The python environment

Always a fun time trying to run some python. This time I relied on Anaconda.

Followed the installation found [here](https://docs.anaconda.com/anaconda/install/mac-os/) for mac. Then, after enabling the initialization to run, I needed to ensure the setup was configured with zsh.

```
source <path to conda>/bin/activate
conda init zsh
```

Then I disabled the auto_activate_base with..

```
conda config --set auto_activate_base False
```

When I need to use conda (like in the exercises in this repo under "Python"), simply rerun:

```
source <path to conda>/bin/activate
```


