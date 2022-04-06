DO NOT CONNECT TO GPU IN RUNTIME!

DO NOT CONNECT TO GPU IN RUNTIME!

DO NOT CONNECT TO GPU IN RUNTIME!

Please Do not connect to GPU at runtime.

Please go to the Runtime->Change runtime type and select the Hardware accelerator to be None. 

Running the colab notebook actually don't need requirement.txt as the notebook contains code for downloading it at runtime.

Currently, every time we call the rungame function only 1 level of the game will be run. In the notebook, it loop through several levels in a list called levels. Currently this list of levels is genrated by np.random.rand() and contains 60 levels.

# ECE_471_Project_Submission
