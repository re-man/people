People
======
Algorithms related to detecting and tracking people using various robot sensors.

Changes
^^^^^^^^^^^^^
Changed leg_detector.launch
Line 3: args="scan:=base_scan -> args="scan:=scan"
to make it work with Hokuyo UST-10LX

Documentation
^^^^^^^^^^^^^
http://ros.org/wiki/people

Requirements & building
^^^^^^^^^^^^^^^^^^^^^^^
This project depends on ROS and can be built using catkin.

Branches
^^^^^^^^
fuerte_trunk - Most recent version for Fuerte. This version is not maintained.

groovy-devel - Most recent version for Groovy. Bug fixes only.

groovy - Catkinized version for Groovy - Released as deb. 

hydro-devel - Most recent version for Hydro. Bug fixes only.

indigo-devel - Most recent version for Indigo. Bug fixes and stable new features.

master - Really new features, may not be stable. Currently developing against Hydro.

