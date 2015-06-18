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

### Install participant applications

* Log on https://challenges.esa.int
* Go to _Ocean Colour Atmospheric Correction_ Data Challenge
* Open the _Applications_ tab
* If needed refresh to load the latest applications releases from GitHub
* Select the latest application release and copy the URL
* Log on the Evaluation Environment
* Run the command below:

```bash
eceo-getrelease <URL copied earlier
```
 
 * Then install it with:
 
```bash
sudo yum install <RPM name>
```


