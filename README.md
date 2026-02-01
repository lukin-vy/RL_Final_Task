# RL_Final_Task
Сессионное задание по дисциплине "Обучение с подкреплением"

### Запус через pip:

1) Создание нового окружения:

```
(Linux)
python3 -m venv .rl

(Windows)
python -m venv .rl
```

2) Активация нового окружения:

```
(Linux)
source .rl/bin/activate

(Windows)
.\.rl\Scripts\Activate.ps1
```

3) Установка необходимых зависимостей:

```
pip install jupyterlab ipykernel numpy pandas matplotlib
pip install -c pytorch -y pytorch torchvision torchaudio cpuonly
pip install -U "gymnasium>=0.29" "stable-baselines3[extra]>=2.2" "imageio>=2.31" "imageio-ffmpeg>=0.4.9"
```

4) Запуск Jupyter:

```
jupyter lab
```


### Запуск через conda:

1) Создание нового окружения:

```
conda create -n rl python=3.10 -y
```

2) Активация нового окружения:

```
conda activate rl
```

3) Установка необходимых зависимостей:

```
conda install -c conda-forge -y jupyterlab ipykernel numpy pandas matplotlib ffmpeg
conda install -c pytorch -y pytorch torchvision torchaudio cpuonly
pip install -U "gymnasium>=0.29" "stable-baselines3[extra]>=2.2" "imageio>=2.31" "imageio-ffmpeg>=0.4.9"
```

4) Запуск Jupyter:

```
jupyter lab
```
