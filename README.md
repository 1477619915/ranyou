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

Under the CVRP/TSP folder, use the default settings in config.yml, run
   ```bash
   python test_cvrplib.py
   python test_vrplib.py

dasd
