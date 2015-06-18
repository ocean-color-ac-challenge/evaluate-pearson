# evaluate-pearson

### Installation

```bash
sudo yum install -y miniconda-3.8.3
export PATH=/opt/anaconda/bin/:$PATH
sudo conda install -y ipython-notebook
sudo conda install -y pandas scipy numexpr
sudo yum install -y aria2
```

```bash
export PATH=/opt/anaconda/bin/:$PATH
git clone git@github.com:ocean-color-ac-challenge/evaluate-pearson.git
cd evaluate-pearson 
git checkout develop
ipython notebook --ip=<evaluation VM IP>
```

Open the Browser at the VM IP and port 8888

