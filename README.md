# python-analytics

### 初期
```
apt-get update
```

### Anacondaインストール
```
apt-get install wget -y 
cd /bin 
wget https://repo.continuum.io/archive/Anaconda3-2020.07-Linux-x86_64.sh 
sh Anaconda3-2020.07-Linux-x86_64.sh 
echo 'export PATH=/path/to/anaconda3/bin:$PATH' >> ~/.bashrc
conda list 
conda update --all 
```

### git 
```
apt-get install git -y 
git clone https://github.com/suzudai/python-analytics.git 
```

### jupyter notebook
```
jupyter notebook --ip=0.0.0.0 --allow-root --LabApp.token='' 
```
