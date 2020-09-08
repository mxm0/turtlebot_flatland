# turtlebot_flatland
Turtlebot nav stack/move base integration demo

To start:

Check out [flatland](https://github.com/avidbots/flatland) and turtlebot_flatland into your repository, catkin_make, source your devel/setup.bash and run:
~~~~
roslaunch turtlebot_flatland turtlebot_in_flatland_[floor].launch
~~~~

The repo contains maps downloaded from the NAVVIS department at TUM  [[1]](#1).

## References
<a id="1">[1]</a> 
LMT2014-875,
  author = "Dominik van Opdenbosch AND Georg Schroth AND Robert Huitl AND Sebastian Hilsenbeck AND Adrian Garcea AND Eckehard Steinbach",
  title = "Camera-based Indoor Positioning using Scalable Streaming of Compressed Binary Image Signatures",
  booktitle = "{IEEE} International Conference on Image Processing ({ICIP} 2014)",
  month = "Oct",
  year = "2014",
  address = "Paris, France"
