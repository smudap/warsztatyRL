# Warsztaty Reinforcement Learning

## Teoria

![ ](https://www.52coding.com.cn/images/aae.png )

### Markov process

![ ](https://www.52coding.com.cn/images/markov.png)

### Markov reward process

![ ](https://www.52coding.com.cn/images/mrp.png)

![ ](https://www.52coding.com.cn/images/gamma0.9.png)

![ ](https://www.52coding.com.cn/images/gamma1.png)

### Markov decision process

![ ](https://www.52coding.com.cn/images/mdpstu.png)

### Bellmann equation

![ ](https://cdn-images-1.medium.com/max/1600/1*jamiG5MkFVHLTFmLggemVg.png)

### Q-learning

![ ](https://wikimedia.org/api/rest_v1/media/math/render/svg/9c389edfb9c4342c07a9adad55a3f554a8d2242c)

## Warsztaty

### Instalacja

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
