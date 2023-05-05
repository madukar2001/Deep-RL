To run the project - 

1. Install Anaconda Environment on your system.
2. Open command prompt and run following commands:
        conda config --add channels conda-forge
        conda create --name RL python=3.7 jupyter numpy scipy matplotlib gym
        conda activate RL
        pip install tensorflow=2.1.0
        pip install pygame
        pip insall keras-r12
3. Open VS Code inside the Conda workspace.
4. Open the folder and run main.py file.
5. If asked for any other libraries, install and rerun the main.py file.
6. The game open ups and provide you some sort of moves. Press -
        R for Reset
        Q for Quit
        Space for Random moves
        S for Best Move