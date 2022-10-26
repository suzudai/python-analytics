# python-analytics

### 初期
```
apt-get update
apt-get install vim -y
```

### Anacondaインストール
```
apt-get install wget -y 
cd /bin 
wget https://repo.continuum.io/archive/Anaconda3-2020.07-Linux-x86_64.sh 
sh Anaconda3-2020.07-Linux-x86_64.sh 
echo 'export PATH=/path/to/anaconda3/bin:$PATH' >> ~/.bashrc
source ~/.bashrc
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
### Pyspark構築
```
apt-get install openjdk-8-jre -y
cd /opt
wget https://dlcdn.apache.org/spark/spark-3.3.0/spark-3.3.0-bin-hadoop3.tgz
tar -xvzf ./spark-3.3.0-bin-hadoop3.tgz
echo 'export SPARK_HOME=/opt/spark' >> ~/.bashrc
echo 'export PATH=$PATH:$SPARK_HOME/bin:$SPARK_HOME/sbin' >> ~/.bashrc
source ~/.bashrc
```
