# gladas
Gesture Learning for Advanced Driver Assistance Systems

![Simulation-Based Learning](pictures/GLADAS.png)

## Welcome to GLADAS

GLADAS is an open-sourced research platform for investigating Human-AV Interactions. Specifically, GLADAS is built for the training, testing, validation, and benchmarking of hand gesture recognition algorithms of self-driving cars. Although this repo provides an example algorithm for usage, research teams are free to test and benchmark their own algorithms.

## Requirements

Unreal Engine with AirSim Compatibility ([link](https://www.unrealengine.com/en-US/))

AirSim Package ([installation tutorial](https://microsoft.github.io/AirSim/docs/unreal_custenv/))

AirSim-Python Package
```
pip install msgpack-rpc-python
```
(optional) 3D map for self-driving car research and driving

(optional) Pedestrian with Animated Gestures

## The Code
BenchmarkMetrics: Measures algorithm performance.
    
    *Includes support for Precision-Recall, PR Graphs, F1, Accuracy, TN, TP, FP, FN Metrics*

CarTest: Gives feedback and data on the hand gesture recognition algorithm's performance. Includes the Video Streamer. Resulting data saved to /data/ScenarioX.csv for each scenario.

CarSim: A real-time visualization of CarTest.

Classifier: The Gesture Classifier model used as an example for GLADAS testing. This, as long as most of CarTest, can be changed to fit each individual research team's requirements and specifications.

## Paper
Full instructions and explanation of the code are coming soon.

## Contributors
Ethan Shaotran

Jonathan Cruz (Harvard University)

Vijay Janapa Reddi (Harvard University)

## Contact
Ethan Shaotran (shaotran@mit.edu)
