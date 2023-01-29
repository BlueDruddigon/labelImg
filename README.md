# Instructions

### Ubuntu

```bash
conda create -n env python=3.7
conda install pyqt=5
conda install -c anaconda lxml
make qt5py3
python labelImg.py

```

### Windows 10

```powershell
conda create -n env python=3.7
conda install pyqt=5
conda install -c anaconda lxml
pyrcc5 -o libs/resources.py resources.qrc
python labelImg.py

```
