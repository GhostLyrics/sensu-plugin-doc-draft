## sensu-plugins-large-example: metrics-third.rb

*Note: all lowercase*

Measures all values of sox in the example.

**parameters:**

- `scheme`: The scheme how to label your metrics

**values:**

- `sox.disk_capacity`: How many voxels currently fit into the sandbox. (voxels)
- `sox.radiator_consumption`: How many ions are shot into the radiator per second (ions/second)

*Note: Short descriptions what is measured so that it's easy to understand what is measured if the plugin outputs a high amount of different, complex values*

**requirements:**

- python package ZZLIBWOW must be installed
