# MSE 434 - Joint Transportation and Inventory Project (JTIP)

This repository contains code files for the Joint Transportation and Inventory Problem (JTIP) explored in our MSE 434 group project. The objective is to optimize transportation routes and inventory costs using a combination of heuristics and optimization techniques.

## File Descriptions

- **MSE434_Group5_JTIP.ipynb**  
  This is the main base notebook that implements the standard JTIP model. It sets up the optimization problem including demand, safety stock, and vehicle constraints.

- **MSE434_Group5_JTIP_Nearest_Neighbour.ipynb**  
  This notebook introduces a nearest neighbour heuristic to generate route suggestions before solving the optimization model. It’s useful for reducing solution complexity by narrowing down possible routes.

- **MSE434_Group5_JTIP_Nearest_Neighbour_Extension.ipynb**  
  This builds on the nearest neighbour version and adds more realistic constraints—such as limited fleet size and the inclusion of private carriers. It provides a more practical formulation compared to earlier versions.

- **mse_434_paper_data.xlsx**  
  Contains the input data used in the optimization models, including plant locations, consumption rates, and safety stock requirements.
