## Installation
```
conda env create -f environment.yml
source activate dl
git submodule update --init --recursive
cd gym
pip install -e .
pip install gym[atari]
cd ..
jupyter notebook <dir/assignment>
```
