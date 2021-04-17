# GirlsDay2021
## [Fertiges Notebook](https://mybinder.org/v2/gh/pcbraemer/GirlsDay2021/HEAD?filepath=GirlsDay2021.ipynb)

## Installation
Installation von Jupyter Notebooks lokal:
```bash
pip install notebook
```
Außerdem wird [CMake](https://cmake.org/download/)benötigt. Nach Download und Installation muss man noch den folgenden Befehl ausführen:
```bash
PATH="/Applications/CMake.app/Contents/bin":"$PATH"
```

Starten von Jupyter Notebooks:
```bash
jupyter notebook
jupyter notebook filename
```

Für die offline Installation müssen im Notebook noch Dependencies geladen werden, dafür den folgenden Code ins Notebook kopieren:
```bash
!pip -q install tensorflow==2.3.1 pyglet==1.5.11 gym keras-rl2 'gym[atari]' gym-notebook-wrapper
```

Die Ausführung erfolgt über [Binder](https://mybinder.org), da wird dieses Repository verlinkt.
