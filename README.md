# ECG-detection

This project trains and evaluates deep learning models to classify ECG recordings into diagnostic superclasses using the PTB-XL dataset, a large publicly available 12-lead ECG dataset.

To run:
python3 -m venv ecg_env
source ecg_env/bin/activate
pip install -r requirements.txt

create config.py
add path to dataset on your computer to config.py

jupyter notebook main.ipynb
