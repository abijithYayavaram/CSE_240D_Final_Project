# CSE_240D_Final_Project
Scale-sim enhancements

## SETUP
For running our code, you need to clone two repositories:
1) Scale-Sim v2 repo link - https://github.com/abijithYayavaram/scale-sim-v2/tree/main
2) Krittika repo link - https://github.com/abijithYayavaram/krittika

Follow these steps:
1) Create a top level directory (name does not matter)
2) Create a virtual environment inside this called env (Run `python3 -m venv ./env`) Make sure to use Python (version > 3.6).
3) Activate the venv using: `source env/bin/activate` (Use bash shell)
4) Clone both the repositories mentioned above in the top level directory like this:
     -- top
         -- scale-sim-v2
         -- krittika
5) Run `pip install -r requirements.txt` inside both the repositories to install the dependencies into your venv.
6) Also, add both scale-sim-v2 and krittika folders into your $PYTHONPATH

Now the setup part is done.

## RUNNING THE CODE
Run the code using: `python krittika-sim.py -c ../configs/krittika.cfg` in `/top/krittika/krittika/` directory.

Make appropriate changes in the following files - 
1) You can change the layer you want to run it for by modifying the default argument for topology file in line number 20 of `krittika-sim.py` .
2) In `krittika/configs` folder, modify `krittika.cfg` accordingly for changing number of cores, SRAM memory sizes etc.


Note: In our laptops, we couldn't run bigger layers and more layers due to limited compute resources
