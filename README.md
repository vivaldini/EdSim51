## EdSim51
EdSim51 Simulator Installation

Download the EdSim51 simulator from [this link](http://www.edsim51.com/8051simulator/edsim51di.zip).


### Dependencies
#### Windows

[Java Intallation](https://www.java.com/en/download/)

#### Linux

```bash
sudo apt install openjdk-11-jdk
```

### Unzip

Once you've downloaded the zip file, extract it.
 `edsim51di.zip` contains a folder called `lib` and a JAR file called `edsim51di.jar`. `lib` and `edsim51di.jar` must be kept together in the same location.

![image](https://github.com/vivaldini/EdSim51/assets/74054598/674f2222-f31b-4f2e-b383-d7d13337c302)


### Launching the EdSim51 Simulator

#### Windows

To launch the simulator, double-click on `edsim51di.jar`.

#### Linux

First time launching: Right-click on `edsim51di.jar` and select Properties. Then click on the Permissions tab. Check the "Allow executing file as program" box and then click on Close. You only need to do this once. 

![Screenshot from 2024-03-30 15-32-32](https://github.com/vivaldini/EdSim51/assets/74054598/115f4d3a-fd13-4534-909e-fec23d8fca67)


To launch the simulator, navigate to the folder containing `edsim51di.jar` in your terminal and run the following command:

```bash
java -jar edsim51di.jar
```
