EPR (Elite-Pattern Reinforcement) 

Train EPR-POMO on CVRP or TSP
First， pip install hgyese or lkh
Second, generate the validation sets by generate_data.py
Third, Modify the *load_checkpoint* config in *config.yml* to Null (i.e., *load_checkpoint*: )
Last, run train.py (Since heuristic methods are used to generate elite solutions, a hgs_costs.pt file will be generated.)

Test EPR-POMO on CVRP or TSP
Under the CVRP/TSP folder, use the default settings in config.yml, 
run test_cvrplib.py or test_vrplib.py

Test EPR on POMO、Omni-POMO、Sym-POMO、ELG-POMO
We provide EPR implementations based on various POMO variants. Since the data files are large, you will need to download them yourself from their official repositories. The links are provided below:
POMO：https://github.com/yd-kwon/POMO
Omni-POMO：https://github.com/yd-kwon/POMO
Sym-POMO：https://github.com/alstn12088/Sym-NCO
ELG-POMO：https://github.com/lamda-bbo/ELG
