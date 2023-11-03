# GF130_CARAVEL_PROJ_ACCEL
Accelerator Design process using GF180 for MPW1 

## Setting Tools and PDKs for ```gf180mcu```

1.  Get Docker (or a compatible container engine)
    -  On Ubuntu, follow the Docker post install instructions after you install Docker.
    -  Get Python 3.6 or higher (macOS | Ubuntu)
    -  On Ubuntu, you may also need to install venv: ```apt-get install python3-venv```, and pip: ```apt-get install python3-pip```.
    -  Get git (macOS | Ubuntu)
    -  Get GNU Make (macOS | Ubuntu)

2.  Run the following commands in your command-line prompt:

```
cd $HOME
git clone https://github.com/The-OpenROAD-Project/OpenLane
cd OpenLane
make
make test
```
After ```OpenLane``` is set up on your computer. To enter the ```OpenLane``` environment, cd ```$HOME/OpenLane``` and then ```make mount```.
