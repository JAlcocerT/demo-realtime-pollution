<div align="center">
  <h1>Taipy Demo</h1>
</div>

<div align="center">
  <h3>Real Time Data</h3>
</div>


<div align="center">
  <h4>LangChain | LlamaIndex | PandasAI | HayStack</h3>
</div>

<div align="center">
  <a href="https://github.com/JAlcocerT/Streamlit-MultiChat?tab=GPL-3.0-1-ov-file" style="margin-right: 5px;">
    <img alt="Code License" src="https://img.shields.io/badge/License-GPLv3-blue.svg" />
  </a>
  <a href="https://www.python.org/downloads/release/python-311">
    <img alt="Python Version" src="https://img.shields.io/badge/python-3.11-blue.svg" />
  </a>
</div>



<details>
  <summary>Get Python and the env ready to run the Flask Web App 👈</summary>
  &nbsp;

```sh
sudo apt update
sudo apt install build-essential software-properties-common -y
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt update

sudo apt install python3.11 -y
```

```sh
sudo apt install python3-pip
sudo apt install python3.10-venv
#apt install python3.12-venv
#sudo apt install python3.12-dev
```


```sh
git clone https://github.com/JAlcocerT/flask_sensor_display
#git clone https://github.com/KarolPWr/flask_sensor_display.git
#git checkout tags/v1.0.0
```

```sh
#python -m venv solvingerror_venv #create the venv
python3 -m venv taipy_webapp_venv #create the venv

#solvingerror_venv\Scripts\activate #activate venv (windows)
source taipy_webapp_venv/bin/activate #(linux)
```

```sh
sudo apt update

sudo apt upgrade g++ #this is important!
sudo apt install build-essential python3-dev  # or python-dev for older Python versions

pip3 install -r requirements.txt
```

</details>

```sh
python3 receiver.py
python3 sender.py
```

> Forked from https://github.com/Avaiga/demo-realtime-pollution

---

# Realtime Pollution Dashboard

A use-case of measuring air quality with sensors around a factory to showcase the ability of Taipy to dashboard streaming data.

<p align="center">
  <img src="media/dashboard.png" alt="Dashboard" width="100%"/>
</p>

## How to use

1. Clone this repository

```bash
git clone https://github.com/Avaiga/demo-realtime-pollution.git
```

2. Install requirements

```bash
pip install -r requirements.txt
```

3. Run the receiver script

```bash
python receiver.py
```

This should open a dashboard in your browser.

4. Run the sender script

```bash
python sender.py
```

This will send data to the dashboard.