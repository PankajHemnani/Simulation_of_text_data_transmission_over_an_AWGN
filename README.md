# Simulation of text data transmission over an AWGN
## GOAL
To write a python code on an encoding-decoding technique for text data so that the received signal can be detected correctly after addition of unwanted noise during its transmission.
## COMPONENTS OF CODE
There are 7 major component in our code which are
1. **Signal Encoding** - Fixed length encoding method was used for signal encoding.
2. **Channel Encoding** 
3. **Modulator** - BPSK method was used for modulation of signal.
4. **Adding of Noise (Additive White Guassian Noise)**
5. **Demodulator**
6. **Channel Decoding**
7. **Signal Decoding**

## Prerequisites Packages

```
python3 pip install numpy
```

## Libraries used in code
1. To use arrays used in our code, we used library named as:
```
numpy
```
2. For plotting curve to show the results statistically, we used library named as:
```
matplotlib
```
## GUIDE TO USE THE CODE
1. Import all the libraries used in the code.
1. The text you want to pass, give that to the variable: **TextToBeEncoded** 
2. You can change the Standard Deviation in CHANNEL NOISE i.e in AWGN (More the Standard Deviation more will be the Errors while Decoding)
## OUTPUT
You will get your text parsed and Your output Depends on the Standard Dviation.
