

# Deep Imitation Learning for Bimanual Robotic Manipulation


Code for NeurIPS 2020 paper "Deep Imitation Learning for Bimanual Robotic Manipulation" (https://arxiv.org/abs/2010.05134

Code is implemented with PyTorch. Data can be generated using the "Simulation Code"


The prediction models are titled Table_Lift_HDR-IL for the table lifting task, and Peg In Hole HDR-IL for the peg-in-hole task referenced in the paper. Details about training the model can be found in "Model_Readme.txt"

# Demonstrations
We created the following demonstrations in PyBullet. Our model learns to imitate these movements and generalizes them to tables at different locations.

## Table Lifting Simulation                                                 

![](https://github.com/Rose-STL-Lab/HDR-IL/blob/master/tablelift.gif)       

## Table Lifting and Connecting Simulation   

![](https://github.com/Rose-STL-Lab/HDR-IL/blob/master/tableliftconnect.gif)      




# Generating Data

All code for generating training data is found in the "simulations" folder. Simulations are built up using low-level primitives such as lift or push. All simulations are written using the PyBullet physics engine. All components in the simulations are built-up using URDF files. These files can be easily extended to create other objects/tasks to be used in simulations. In order to save time, simulations are best run on a workstation with a GPU.



# Citation
To cite our work:

@misc{xie2020deep,
      title={Deep Imitation Learning for Bimanual Robotic Manipulation}, 
      author={Fan Xie and Alexander Chowdhury and M. Clara De Paolis Kaluza and Linfeng Zhao and Lawson L. S. Wong and Rose Yu},
      year={2020},
      eprint={2010.05134},
      archivePrefix={arXiv},
      primaryClass={cs.RO}
}


# Authors

Fan Xie
Alex Chowdhury








