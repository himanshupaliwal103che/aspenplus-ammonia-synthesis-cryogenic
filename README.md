# aspenplus-ammonia-synthesis-cryogenic
Aspen Plus simulation of cryogenic ammonia synthesis using equilibrium reactor, membrane separation, and flash system with process optimization and property method comparison.
This project models and simulates the synthesis of ammonia (NH₃) from a mixture of N₂, H₂, CH₄, and Ar using Aspen Plus.  
## Process Overview
- **Feed Composition:** N₂ (24%), H₂ (74%), CH₄ (1%), Ar (1%)  
- **Operating Conditions:** 5000 kmol/h feed, 50 °C, 90 bar  
- **Reaction Modeling:** Equilibrium reactor (minimization of Gibbs free energy)  
- **Separation:**  
  - Reactor effluent is depressurized to 15 bar via valve  
  - Stream is flashed at –35 °C to recover liquid ammonia  
  - Vapor stream is sent to membrane separator (90% H₂ + N₂ recycled, 10% purge)  
- **Compression:** Recycle stream compressed back to reactor pressure (isentropic efficiency 90%, mechanical efficiency 80%)  
## Key Features
- Comparison of **property methods**: Ideal, NRTL, Peng–Robinson  
- Optimization for **99.8% NH₃ purity**  
- Simulation of cryogenic flash separation and recycle loop  
- Integration of reactor, flash, membrane, and compressor units
- ## Results
- Product ammonia stream meets purity constraint of **99.8%**  
- Analysis of different property methods and their accuracy in predicting ammonia production 
