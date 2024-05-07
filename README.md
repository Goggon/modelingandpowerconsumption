# About
This repository is for reproduction of the figures 12, 13 and 14 from the article Modelling and Analysis of DTLS: Power
Consumption, and Attacks.

## reproduction of figures
Firstly, the needed pip packages used in the scripts can be gotten via the command:
```
pip install -r requirements.txt
```

Then run the following command with the path to the UPPAAL installation directory as an argument:
```
generate.py --uppaal PATH_TO_UPPAAL
```

The figures will be generated in the `figures` directory.

## Info about the models
The models are located in the `models` directory. The models are the same as the ones used in the paper.

In the global declarations of the models, there is a variable called `enablePerformanceMeasures` which enables or disables the use of the symbolic model checking.