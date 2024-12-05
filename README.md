## Installation matlab

## option 1  
### 1. Copy the installation package to your folder
if you have your installation package, skip this step

if you have a matlab account，you can use this installation package
```bash
cd ~/tools
mkdir matlab
cd matlab
cp -r /home/eedy/tools/matlab/matlab_2023a .
chmod a+x -R ./*
```
### 2. Install matlab
```bash
cd matlab_2023a
./install
```
In the graphical interface, select your own installation path, e.g.:/home/eedy/tools/matlab/matlab2023a

### 3. Setup
Create an alias matlab in ~/.bash_profile file for easy activation, e.g.:
```bash
alias matlab='~/tools/matlab/matlab2023a/bin/matlab'
```
### 4. Test the installation
Run the following to test the installation
```bash
# if you make alias matlab
matlab
```
or 
```bash
# if you do not make alias matlab
cd ~/tools/matlab/matlab2023a/bin
./matlab
```

## option 2
### 1. Copy matlab to your folder
```bash
mkdir tools
cd ~/tools
mkdir matlab
cd matlab
cp -r /home/eedy/tools/matlab/matlab2023a .
chmod a+x -R ./*
```
### 2. Test the installation
Run the following to test the installation
```bash
cd ~/tools/matlab/matlab2023a/bin
./matlab
```
