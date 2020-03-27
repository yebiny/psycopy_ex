# PreConn


Building Experiments in PsychoPy


## Sturcture

├── 1-FSO_roi\
│   ├── README.md\
│   ├── exe_this.py\
│   ├── make_matrix.py\
│   ├── stim\
│   └── structure.psyexp\
├── 2-SO_localizer\
│   ├── README.md\
│   ├── exe_this.py\
│   ├── make_matrix.py\
│   ├── ordering.py\
│   ├── stim\
│   └── structure.psyexp\
├── 3-Diamond\
│   └── README.md\
├── README.md\
├── check_stim.ipynb\
├── psychopy-env.yml\
└── subjects\
    ├── README.md\
    ├── make_subdir.sh\
    ├── read_csv.py\
    └── test\

## 1. Setting 

경로: ./PreConn/

* Anaconda and Miniconda를 이용해 psychopy환겅을 만들어 줍니다. 
> conda env create -n psychopy -f psychopy-env.yml

* 설치 후 아래 명령어를 통해 만들어진 환경을 확인합니다. 
> conda env list

* psychopy 환경을 실행합니다. 
> conda activate psychopy

------
