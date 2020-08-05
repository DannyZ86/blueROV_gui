# blueROV_gui

## Overview

**Author(s):** Daniel Zatko, Anton Danylenko

**Maintainer:** Daniel Zatko <dzatko@stevens.edu>

**Operating system(s):** Ubuntu Linux


## Content
“This material is based upon work supported by the U.S. Department of Homeland Security under Cooperative Agreement No. 2014-ST-061-ML0001. The views and conclusions contained in this document are those of the authors and should not be interpreted as necessarily representing the official policies, either expressed or implied, of the U.S. Department of Homeland Security.”


This file will walk you through setting up the BlueROV Graphical User Interface on the ROS framework

1. The rqt_multiplot plugin must be installed for the interface to work

Installation 
  ```shell 
  $sudo apt-get update
  $sudo apt-get install ros-DISTRO-rqt-multiplot
  ```
2. Open roscore

  $roscore

3. Open rqt_gui

  $rosrun rqt_gui rqt_gui

4. Import perspective file

  Click on the perspectievs drop down menu
  Click Import
  Navigate to the blueROV_gui.perspective file in this folder
  Open
  
5. Import the multiplot .xml file

  Click on the "Open Configuration" tool under the rqt_multiplot plugin
  Navigate to the "rqt_multiplot.xml" file in this folder
  Open
