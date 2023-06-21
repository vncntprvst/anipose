**Installation 06/20/23**

conda create -n anipose python=3.8 tensorflow=2.3.0 ffmpeg
conda activate anipose

python -m pip install deeplabcut
python -m pip install -U wxPython
python -m pip install anipose
pip install mayavi