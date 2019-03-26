# Evolving-Robots-Using-Evolutionary-Algorithm

THE ASSOCIATED WORK FOR THIS PROJECT CREDIT TO ZHENGYANG DU AND JERRY ZHANG

This project contains three phases:

    1. Building a cube with 8 nodes and 28 springs connected between the 8 nodes in Vpython. The motion and force reaction were simulated as in reality. The spring force reactions were updated and calculated simultaneously at each time step to make sure the cube can bounce and move like a real cube in reality.
    
    2. Applying evolutionary algorithm to the cube by giving each spring a certain oscillating rate. The goal was to make the cube learn how to move. Therefore, the parameters in the equation of oscillation such as L = L0 + a*(sin(theta)+b) are stored as genes. For each iteration, multiple parameter sets were applied to certain springs in the cube and through selection, mutation, and crossover, certain good parameters (parents and offsprings) with high movement distance of center of mass were selected into the next generation. In order to keep the diversity at a reasonable level, the deterministics crowding techniques were applied which was to compare the performance of a pair of parents and a pair of offsprings each time to pick the best two instead of picking the next generation depending only on the final performance ranking. The evolved cube was presented in the report and the methodologies were presented in the code.
    
    3. The final pahse for this project was to make multiple cubes and and evolve the performace and the shape of the bigger cube (formed by single cubes from phase 2). Similar approach was applied using evolutionary algorithm. Instead of using direct encoding such as what has applied in phase two, indirect encoding could be applied to make the algorithm more efficient and boost the performace. Genetic programming can be applied as well to evolve a really good robot cube with better shapes.
    
    All of the project was done in simulation via Vpython module. The specific code for each phase of the project can be found in each of the report.
