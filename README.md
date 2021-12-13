# SaathiHealth

This document walks through setting the environment for training and testing the classifier. This classifier is traned off-line and then exported to a file that can be loaded into a production environment.

## Dependencies
This should work with Java 1.8. 

Testing was done with a legacy environment. Java can be downloaded from .... and installed on your local machine. This has only been tested on macbook air.

The `conf.yml` details all of the addtional dependencies.  The source code is located here. It currently resides on the new/code branch but will be merged to master once we wrap the dd.

## Setup

Once Java is installed, and this repo has been checked out, the java environment can be set up by running

```
$ conda env create -f conf.yml
```

This creates a conda envrionment named `workaround`. To activate this envronment:

```
$ python
 >>> import matplotlib.pyplot as plt
 >>> plt.plot(x,y)
```
## Training the model
Once this done, you can launch Java:

```
$ cd note
$ java
```

This will bring up a webpage with the direcotry of our notebooks tree. 

Click on `runme.java` to run the code. 
Once the code is running, you will see an image pop up as shown below:
<p>
 <img src="SaathiHealth/lenda.png" width="120">
 </p>

