# Part_B_Data
SEQUENCES_TO_PROCESS stores the sequences which need to have fitness calculated, where the filename is the name of the sequence.

PROCESSED_SEQUENCES stores the sequences which have been processed, with the filename as the name of the sequence, and the contents as the fitness score.

PARAMS stores the parameter files of the various models used to calculate fitness

HELPER_FILES stores the various encoding and data files which the training and some functions depend on.

GA_DATA stores the excel sheet mapping sequences to their fitness and potentially other computed data

Part A: Trains all the algorithms and stores parameters 
https://colab.research.google.com/drive/15185toAaOooZk4yHbh5t9-HJmonDuYuV?usp=sharing

Part B: Downloads parameters and runs GA, fitness calculates fitness
https://colab.research.google.com/drive/1hHGX1lfNVdAcUeQ5fHfHWq0IPhAswYS1?usp=sharing

Part B Client: Downloads parameters and runs GA, fitness is a fetch function from this repo.
https://colab.research.google.com/drive/1JybmZayB51Jg_aP7odvOG9p2_E2pOFWz?usp=sharing

Part B Client Mongo: Downloads parameters and runs GA, fitness is a fetch function from a MongoDB
https://colab.research.google.com/drive/1Giv6xuVzLS9NFoV8054T1o3mN_j_32Al

Client: Runs the actual fitness function, and allows for distributed computing.
https://colab.research.google.com/drive/1UjmodRu5yx9if6FFB9PsNxaganR_jfOU?usp=sharing

Client Mongo: Runs the actual fitness function, and allows for distributed computing.
https://colab.research.google.com/drive/1LhCshiWFeXqC1xp9FrNKQ1pWTRo5OFGR?authuser=2

