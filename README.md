# Airline Crew Scheduling Optimizer

Optimization project for airline crew scheduling using **Set Covering Problem (SCP)**, **Integer Linear Programming (ILP)**, and **Genetic Algorithms (GA)**.  
The project analyzes flight–pairing datasets, formulates crew pairing as an SCP, and evaluates classical optimization (ILP) against evolutionary optimization (GA) in terms of solution quality and computation time.

---

##  Project Workflow
1. **Exploratory Data Analysis (EDA)**  
   - Analyzed flight–pairing dataset for cost structures and coverage.  
   - Visualized distributions, flight frequencies, and pairing feasibility.  

2. **Set Covering Formulation**  
   - Modeled crew scheduling as a **Set Covering Problem (SCP)**.  
   - Solved using **Integer Linear Programming (ILP)** via PuLP.  

3. **Genetic Algorithm Implementation**  
   - Developed a GA with selection, crossover, and mutation operators using DEAP.  
   - Scaled SCP to larger problem sizes where ILP becomes computationally expensive.  

4. **Comparison & Evaluation**  
   - Compared **solution quality** (cost minimization) and **runtime efficiency** between ILP and GA.  
   - Conducted multiple runs for statistical reliability.  

---

## 🛠Methods & Tools
- **Optimization:** Set Covering, Integer Linear Programming, Genetic Algorithm  
- **Libraries:** PuLP, DEAP, NumPy, Pandas, Matplotlib, Seaborn  
- **Visualization:** Convergence plots, cost distribution histograms, flight coverage bar charts, Gantt charts  

---

## Results & Insights
- **ILP** provided optimal solutions for small to medium instances.  
- **GA** achieved near-optimal solutions faster on larger instances.  
- Trade-off observed: ILP guarantees optimality, while GA offers scalability.  

---

## Sample Visualizations
- **Convergence of GA fitness function**  
- **Flight coverage distribution across pairings**  
- **Pairing cost distribution (histograms)**  
- **Crew assignment Gantt charts**  

---




   git clone https://github.com/your-username/airline-crew-scheduling-optimizer.git
   cd airline-crew-scheduling-optimizer
