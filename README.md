## Installation matlab

### 1. Copy the installation package to your folder
```bash
cd ~/tools
mkdir matlab
cp -r /home/eedy/tools/matlab/matlab_2023a .
```
### 2. Install matlab
```bash
cd matlab
./install
```
In the graphical interface, select your own installation path, e.g.:/home/eedy/tools/matlab/matlab2023a

### 3. Setup
Create an alias matlab in ~/.bash_profile file for easy activation, e.g.:
```bash
alias matlab='~/tools/matlab/matlab2023a/bin/matlab'
```
