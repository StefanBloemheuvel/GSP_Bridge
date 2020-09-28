# Graph Signal Processing on Complex Networks for Structural Health Monitoring
Additional material for the paper under review. [PAGE IN PROGRESS]

## Abstract
In this work, we demonstrate the application of a framework targeting Complex Networks and Graph Signal Processing (GSP) for Structural Health Monitoring (SHM). 
By modeling and analyzing a large bridge equipped with strain and vibration sensors, we show that GSP is capable of selecting the most important sensors, investigating different optimization techniques for selection. Furthermore, GSP enables the detection of graph signal patterns (mode shapes), grasping the physical function of the sensors in the network. 
Our results indicate the efficacy of GSP on complex sensor data modeled in complex networks.

## Contributions

### 1. We propose the modeling options taken for making the real-world dataset applicable for GSP using a complex network representation.

### 2. We present comprehensive analysis results, regarding sensor network modeling in a resource-aware way, aiming towards a minimal set of sensors for reconstructing the given signal

![](images/chosennodes.png)

### 3. We provide modeling results on signal pattern and event identification



In the following animation, the increased strain in the bridge is visible in the lower right part of the bridge. We also see a decrease in strain in the top part of the bridge, where the road is placed. 

![](images/vibrationtest.gif)

One could also investigate the Fourier components of the exact same signal, visible in the following animation:

![](images/fourierexample.gif)

The vibration signal of the exact same moment during the traffic event, showing a back-and-forth vibration signal flowing through the concrete structure:

![](images/vibrations.gif)