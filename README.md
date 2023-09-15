# skull_stripping

Github:
1. [BrainPrep](https://github.com/quqixun/BrainPrep)
    - Good orgnization of code, and great pipline
    - the skull stripping code is worth learning. (subprocess and multiprocessing)
2. [brainextractor](https://github.com/vanandrew/brainextractor)
    - Simple implemented the basics of skull stripping from FSL

**Finally use:**
[FSL](https://fsl.fmrib.ox.ac.uk/fsl/fslwiki)
- Download: [Click to download *fslinstaller.py*](https://fsl.fmrib.ox.ac.uk/fsldownloads_registration)

- Install:
    - Type `python fslinstaller.py` in terminal.
    - This setup file will install a new miniconda, and create a new conda enviroment for fsl. (This might take about 5 mins)
    - After install, use `conda env list` to find the enviroment. Use `conda activate <path>` to activate the enviroment.
        - For example, my `<path>` is `/Users/123/fsl`

- Useage: 
    - For GUI: type `fsl` in terminal.
    - For command line for skull stripping, [website](https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/BET/UserGuide) shows how to use it.

- Write code into Python: [BrainPrep skull stripping part](https://github.com/quqixun/BrainPrep/blob/master/src/skull_stripping.py)