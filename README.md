# Part_B_Data
SEQUENCES_TO_PROCESS stores the sequences which need to have fitness calculated, where the filename is the name of the sequence.

PROCESSED_SEQUENCES stores the sequences which have been processed, with the filename as the name of the sequence, and the contents as the fitness score.

PARAMS stores the parameter files of the various models used to calculate fitness

HELPER_FILES stores the various encoding and data files which the training and some functions depend on.

Part A: Trains all the algorithms and stores parameters 
https://colab.research.google.com/drive/145xEG89g0Ui8wUt4G7-WkZapUNmK_A8l#scrollTo=oLufXSgSagCT

Part B: Downloads parameters and runs GA, fitness is a fetch function from this repo.
https://colab.research.google.com/drive/1JybmZayB51Jg_aP7odvOG9p2_E2pOFWz#scrollTo=pR10is3KTFL0

Client: Runs the actual fitness function, allows for distributed computing.
https://colab.research.google.com/drive/1UjmodRu5yx9if6FFB9PsNxaganR_jfOU#scrollTo=3LZ1l7iBiRAV

