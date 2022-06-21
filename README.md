# launch_example
Package with launch file examples. Before reviewing this package, it is recommended to review the [package of publisher and subscriber](https://github.com/ALxander19/subpub_example)

### Example 1 (roslaunch launch_example example1.launch)

Launch just one node, the publisher node inside the src directory in the launch_example package.

### Example 2 (roslaunch launch_example example2.launch)

Launch the subscriber node and include the other launch file, in this case, the first example.

### Example 3 (roslaunch launch_example example3.launch)

Launch two nodes, the publisher and subscriber nodes inside the src directory in the launch_example package.

### Example 4 (roslaunch launch_example example4.launch)

Launch two nodes inside a group, the topics opens from this launch have the name of the group before its own name.

### Example 5 (roslaunch launch_example example5.launch)

Add a parameter specified for the launch file. This parameter make the count start with the value asigned inside the launch file.

### Example 6 (roslaunch launch_example example6.launch)

Define the value, to start the count, outside the node. This value cannot be change from the terminal.

### Example 7 (roslaunch launch_example example7.launch)

Define the value, to start the count, outside the node. This value can be change from the terminal, but if not it has a default value.
