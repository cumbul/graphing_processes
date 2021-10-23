# Graphing Processes
Implemented to graph processes in xv6. Thanks [joshmin98](https://github.com/joshmin98) for his contributions.

## 1 - Install dependencies
  
### Check if you have python3, if not install python3
  
```
python3 --version
```

### Install pip3

#### For Ubuntu 
```
sudo apt-get -y install python3-pip
pip3 --version
```
#### For Mac
```
python3 -m pip install --upgrade pip
pip3 --version
```
  
### Install matplotlib and numpy

```
python3 -m pip install -U matplotlib
python3 -m pip install -U numpy
```

if it asks for upgrade use:

```
python3 -m pip install --upgrade pip

```

## 2- Create a target file and output file names
```
touch target_file
touch output_file
```
  
## 3 - Edit target file and paste the output of your tests.

> At the beginning of each pstat array (process) put `PSTAT_START` and at the end put `PSTAT_END`
  
## 4 - Run
```
python3 graphify.py target_file output_file
``` 
