# Trivial-Navigation-System
Interactive Python plotter for selecting start/end points on a map. C++ server computes the shortest path using a graph search algorithm and returns waypoints to the plotter for dynamic route visualization.

Instructions for Running the Navigation System
To test the full navigation system, follow these steps:

1.Open two terminals using gnome-terminal or a similar terminal emulator.

2.In the first terminal, navigate to the soln directory and run the server using the following command:
Ensure the server is running before proceeding to the next step.

3.In the second terminal, also in the soln directory, run the client with the following command:
Make sure to run the client only after the server is successfully started.

Note:
The server must be running before starting the client to avoid an "Unable to make a fifo" error.
If encountering this error due to unexpected termination, manually delete inpipe and outpipe in the soln directory to resolve the issue.
