# EPR (Elite-Pattern Reinforcement)

This repository provides the implementation of **EPR (Elite-Pattern Reinforcement)** based on various POMO variants.

---

## 🚀 Train EPR-POMO on CVRP or TSP

1. **Install dependencies**  
   Install `hgyese`, or `lkh`:
   ```bash
   pip install hgyese or lkh
2. **Generate the validation sets:**
   ```bash
   python generate_data.py
3. **Modify the load_checkpoint config in config.yml**
4. **run train**
   Since heuristic methods are used to generate elite solutions, a hgs_costs.pt file will be generated.
   ```bash
   python train.py

## 🚀 Test EPR-POMO on CVRP or TSP

1. **Under the CVRP/TSP folder, use the default settings in config.yml, run**
   Since heuristic methods are used to generate elite solutions, a hgs_costs.pt file will be generated.
   ```bash
   python test_cvrplib.py
   python test_vrplib.py
   
## 🚀 Test EPR on POMO、Omni-POMO、Sym-POMO、ELG-POMO
1. **We provide EPR implementations based on various POMO variants. Since the data files are large, you will need to download them yourself from their official repositories. The links are provided below:**
POMO：https://github.com/yd-kwon/POMO
Omni-POMO：https://github.com/yd-kwon/POMO
Sym-POMO：https://github.com/alstn12088/Sym-NCO
ELG-POMO：https://github.com/lamda-bbo/ELG
