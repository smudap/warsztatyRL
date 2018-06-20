# Warsztaty Reinforcement Learning

## Instalacja

Podczas warsztatów będziemy korzystać z wirtualnego środowiska z Pythonem 3.5 (dla Pythona 3.6 powinno też działać). Jeśli ktoś nie ma zainstalowanego `virtualenv`, to robi się to komendą:

```bash
pip3 install virtualenv 
```

Uwaga: Do instalacji niektórych pakietów przyda się `cmake`, który można zainstalować komendą:

```bash
sudo apt-get install cmake
```

Możemy teraz przejść do stworzenia środowiska i instalacji pakietów. 

Zacznijmy najpierw od sklonowania repozytorium:

```bash
git clone https://github.com/smudap/warsztatyRL.git warsztaty_rl
cd warsztaty_rl
```

Gdy jesteśmy już w folderze z repozytorium, tworzymy i aktywujemy wirtualne środowisko, w którym będziemy instalować pakiety:

```bash
virtualenv --python=python3.5 warsztaty_rl
source warsztaty_rl/bin/activate 
```

Pakiety możemy zainstalować na dwa sposoby:

1. Korzystając z pliku `requirements.txt`.
```bash
pip install -r requirements.txt
```

2. Instalując wszystkie pakiety ręcznie.

```bash
pip install gym
pip install atari-py
pip install Pillow
pip install tensorflow==1.8.0
pip install Keras==2.1.6
pip install keras-rl
pip install pandas
pip install matplotlib
pip install jupyter
```
