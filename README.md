# GF130_CARAVEL_PROJ_ACCEL
Accelerator Design process using GF180 for MPW1 

## Setting Tools and PDKs for ```gf180mcu```

1.    Get Docker (or a compatible container engine)
    <ul>
    <li>On Ubuntu, follow the Docker post install instructions after you install Docker.</li>
    <li>Get Python 3.6 or higher (macOS | Ubuntu)</li>
    <li>On Ubuntu, you may also need to install venv: ```apt-get install python3-venv```, and pip: ```apt-get install python3-pip```.</li>
    <li>Get git (macOS | Ubuntu)</li>
    <li>Get GNU Make (macOS | Ubuntu)</li>
    </ul>

3.    Run the following commands in your command-line prompt:

```
cd $HOME
git clone https://github.com/The-OpenROAD-Project/OpenLane
cd OpenLane
make
make test
```
<par>After ```OpenLane``` is set up on your computer. To enter the ```OpenLane``` environment, cd ```$HOME/OpenLane``` and then ```make mount```.

3.    To install PDKs and work with the ```gf180mcu``` digital library you need to install the library within the ```$HOME/.volare``` folder that contains all the PDKs.
    - Make sure that ```volare``` is installed.

<par>Debian 10+ or Ubuntu 18.04+ is required.
```
sudo apt-get update
sudo apt-get install python3 python3-pip xz-utils

# To install (or upgrade)
python3 -m pip install --upgrade --no-cache-dir volare

# To verify it works
volare --version
```
